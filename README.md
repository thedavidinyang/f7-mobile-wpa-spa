# My blank App

## Framework7 CLI Options

Framework7 app created with following options:

```
{
  "cwd": "F:\\NODEJS\\FRAMEWORK7\\sampleblank",
  "type": [
    "web",
    "pwa",
    "capacitor"
  ],
  "name": "My blank App",
  "framework": "core",
  "template": "single-view",
  "bundler": false,
  "cssPreProcessor": false,
  "theming": {
    "customColor": false,
    "color": "#007aff",
    "darkTheme": false,
    "iconFonts": true,
    "fillBars": false
  },
  "customBuild": false,
  "pkg": "io.framework7.myapp",
  "capacitor": {
    "platforms": [
      "ios",
      "android"
    ]
  }
}
```

## Install Dependencies

First of all we need to install dependencies, run in terminal
```
npm install
```

## NPM Scripts

* 🔥 `start` - run development server
* 🔧 `serve` - run development server
* 📱 `build-capacitor-ios` - Copy app to iOS capacitor project
* 📱 `build-capacitor-android` - Copy app to Android capacitor project
## PWA

This is a PWA. Don't forget to check what is inside of your `service-worker.js`. It is also recommended that you disable service worker (or enable "Update on reload") in browser dev tools during development.



## Capacitor

This project created with Capacitor support. And first thing required before start is to add capacitor platforms, run in terminal:

```
npx cap add ios && npx cap add android
```

Check out [official Capacitor documentation](https://capacitorjs.com) for more examples and usage examples.



## Assets

Assets (icons, splash screens) source images located in `assets-src` folder. To generate your own icons and splash screen images, you will need to replace all assets in this directory with your own images (pay attention to image size and format), and run the following command in the project directory:

```
framework7 assets
```

Or launch UI where you will be able to change icons and splash screens:

```
framework7 assets --ui
```

## Capacitor Assets

Capacitor assets are located in `resources` folder which is intended to be used with `cordova-res` tool. To generate  mobile apps assets run in terminal:
```
npx cordova-res
```

Check out [official cordova-res documentation](https://github.com/ionic-team/cordova-res) for more usage examples.

## Documentation & Resources

* [Framework7 Core Documentation](https://framework7.io/docs/)



* [Framework7 Icons Reference](https://framework7.io/icons/)
* [Community Forum](https://forum.framework7.io)

## Support Framework7

Love Framework7? Support project by donating or pledging on:
- Patreon: https://patreon.com/framework7
- OpenCollective: https://opencollective.com/framework7