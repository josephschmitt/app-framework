# App Framework &nbsp; &nbsp; &nbsp; [![](https://img.shields.io/npm/dt/app-framework.svg)](https://www.npmjs.com/package/app-framework) [![](https://img.shields.io/npm/v/app-framework.svg)](https://www.npmjs.com/package/app-framework) [![](https://img.shields.io/npm/l/app-framework.svg)](https://www.npmjs.com/package/app-framework)

**iOS and Android Apps with HTML & JavaScript - develop, build and deploy - free and open source!**

![Process](media/process.png)

## Features

For your application:

- [x] **Single file components** - with template, scripts and style included, ready for [ES2015](https://babeljs.io/learn-es2015/)
- [x] **Beautiful user interface** - with all well-known [iOS and Material](http://framework7.io/) elements and transitions
- [x] **Easy styling** - of the theme, color, layout and the status bar colors and visibility
- [x] **Comprehensive icon fonts** - [FontAwesome](http://fontawesome.io/), [Framework7](http://framework7.io/icons/), [Ion](http://ionicons.com/) and [Material Icons](https://material.io/icons/)
- [x] **Powerful user interface** - state-based and reactive with the simplicity of [Vue.js](https://vuejs.org/)
- [x] **Reliable backend** - with Firebase for [user authentication](https://firebase.google.com/docs/auth/), [realtime database](https://firebase.google.com/docs/database/) and [storage](https://firebase.google.com/docs/storage/)
- [x] **Global data object** - to use the same data and settings across your whole application
- [x] **Flexible routing** - [nestable](http://framework7.io/vue/navigation-router.html) and easily to be protected by required user login
- [x] **State restoration** - for history, tabs, scroll positions, form inputs, focus, modals and components
- [x] **Many more** - like offline capability, multi-language support, ...

For your workflow:

- [x] **Project folder generation** - lightweight, well-organized and ready for Git publishing
- [x] **Local testing** - on a live-server, on your own device or on any iOS or Android simulator
- [x] **Integrated checks** - with automatic fix for code [correctness](http://eslint.org/) and [standard conformity](http://standardjs.com/)
- [x] **Optimized build** - with version bump, icon generation and compression of all files
- [x] **Safe deployment** - without downtime to any FTP server, [Firebase](https://firebase.google.com/docs/hosting/), [Xcode](https://developer.apple.com/xcode/) or [Android Studio](https://developer.android.com/studio)
- [x] **Snapshots** - of the Firebase backend and all project files to backup on any external drive or cloud

## Demo App

[![Download on the App Store Play](media/app-store-download.png)](https://itunes.apple.com/us/app/app-framework-demo/id1203927581?mt=8')
&nbsp;&nbsp;&nbsp;
[![Get it on Google Play](media/google-play-download.png)](https://play.google.com/store/apps/details?id=de.scriptpilot.appframework)
&nbsp;&nbsp;&nbsp;
[![Open as Web App](media/web-app-visit.png)](https://app-framework.scriptpilot.de/)

## Milestones

Upcoming:

- [ ] 1.5 - Demo App robustness improvements
- [ ] 1.6 - Tutorial: ToDo App
- [ ] 1.7 - Extensions
- [ ] 1.8 - GUI helper tool

Reached:

- [x] [1.4 - Client code robustness improvements](https://github.com/scriptPilot/app-framework/milestone/7?closed=1) (2017-05-05)
- [x] [1.3 - CLI robustness improvements](https://github.com/scriptPilot/app-framework/milestone/6?closed=1) (2017-03-19)
- [x] [1.2 - Google Play Store deployment](https://github.com/scriptPilot/app-framework/milestone/5?closed=1) (2017-02-12)
- [x] [1.1 - Apple App Store deployment](https://github.com/scriptPilot/app-framework/milestone/4?closed=1) (2017-02-10)
- [x] [1.0 - Initial Release](https://github.com/scriptPilot/app-framework/milestone/1?closed=1) (2017-02-05)

## Required knowledge

Essentiell:

- [Node.js and npm](https://docs.npmjs.com/getting-started/what-is-npm) for command line interface handling
- [Framework7](https://framework7.io/docs/) and [Framework7-Vue](https://framework7.io/vue/) to develop with HTML and JavaScript

Optional:

- [Vue.js](https://vuejs.org/v2/guide/) to make your application state-based and reactive
- [Firebase](https://firebase.google.com/docs/web/setup) to use as reliable backend service provider
- [Cordova/PhoneGap](https://cordova.apache.org/docs/en/latest/) to use device hardware API plugins
- [iOS design guidelines](https://developer.apple.com/ios/human-interface-guidelines/overview/design-principles/) and [Material design guidelines](https://material.io/guidelines/)

## Quick start

1. Install [Node.js](https://nodejs.org/)
2. Create a **package.json** file in an empty project folder with the following content:

   ```
   {
     "name": "my-app",
     "version": "1.0.0",
     "devDependencies": {
       "app-framework": "*"
     }
   }
   ```

3. Run `npm install` to install App Framework and setup the project folder
4. Run `npm run dev` to run your application at localhost:8080
5. Read our [Documentation](DOCUMENTATION.md)
