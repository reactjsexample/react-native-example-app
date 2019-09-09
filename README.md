# react-native-example-app

**React Native Example App**. A react native starter app with routing and tabs.

Created by **ReactJSExample** [https://github.com/reactjsexample](https://github.com/reactjsexample)

Full source code available at [https://github.com/reactjsexample/react-native-example-app](https://github.com/reactjsexample/react-native-example-app)

## Table of Contents

- [About The Author](#about-the-author)
- [Project Setup](#project-setup)
  - [Prerequisites](#prerequisites)
    - [NodeJS and NPM](#nodejs-and-npm)
    - [Instructions for Mac](#instructions-for-mac)
      - [Mac OS Mojave](#mac-os-mojave)
      - [Xcode 11](#xcode-11)
      - [Expo Client](#expo-client)
      - [React Native Getting Started](#react-native-getting-started)
  - [How To Install](#how-to-install)
  - [How To Run](#how-to-run)
    - [Metro Bundler](#metro-bundler)
    - [Use iPhone on Local LAN](#use-iphone-on-local-lan)
- [Software Libraries Used](#software-libraries-used)

## About The Author

**JC Lango** is a UI Architect and UI Developer for large scale web applications at several Fortune 500 companies.

He is an expert in **Angular**, **Polymer**, and **React** and maintains these sites at Github:

- **AngularExample** [https://github.com/angularexample](https://github.com/angularexample)
- **PolymerExample** [https://github.com/polymerexample](https://github.com/polymerexample)
- **ReactJSExample** [https://github.com/reactjsexample](https://github.com/reactjsexample)

JC may be available to work remote, and can be contacted at these links:

- LinkedIn: [https://www.linkedin.com/in/jclango](https://www.linkedin.com/in/jclango)
- Email: [jobs@jclango.com](mailto:jobs@jclango.com)

## Project Setup

### Prerequisites

#### NodeJS and NPM

You need to have Node and NPM installed on your PC.

[Downloading and installing Node.js and npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)

#### Instructions for Mac

**NOTE**: The following instructions are for Mac.

##### Mac OS Mojave

You need to have Mac OS Mojave, 10.14.6

If you need to upgrade your Mac look this up online.
You also need to install all of the latest upgrades for 10.14.6

##### Xcode 11

You need to install Xcode 11.
The latest version at the time of this writing is Xcode 11 beta 7.
Get this at [Apple Developer](https://developer.apple.com/download/)

##### Expo Client

You need to install the Expo Client on you Mac.

You also need to install the Expo Client App on your iPhone.

You can use the iOS Simulator that comes with Xcode,
but it is better to use an actual iPhone for the development process.

##### React Native Getting Started

The React Native docs explain how to install Expo.

Here is the official docs [React Native Getting Started](https://facebook.github.io/react-native/docs/getting-started)
 
### How To Install

Download the source code using git or else download and unzip the zip file.

Open a terminal window and go to the project root folder.

You need to have npm installed globally.

Run `npm i` to install the required libraries.

### How To Run

Open a terminal window and make sure you are in the project root folder.

Run the following command for a dev server.

`npm start`

After the app builds a browser will open to this address:
Open your browser and go to [http://localhost:19002](http://localhost:19002)

#### Metro Bundler

The browser will have the Metro app, with the Metro Bundler which has the build project.

On the left side of the window at the bottom will be a bar code graphic.

#### Use iPhone on Local LAN

You should have an iPhone, with WiFi connected to the same LAN as your Mac PC.

And the iPhone needs to have the Expo Client app installed.

On the iPhone, open the Camera app, and point the camera at the bar code graphic that is shown in the browser.
It will ask you if you want to open the app in Expo.
After you confirm that, you will see the current screen on your iPhone.

The browser will automatically reload if you change any of the source files.

It may take a minute each time for the app to build.

Open the browser's Developer Tools window to see any errors in the Console.

## Software Libraries Used

These are the main packages used in this app:

- react 16.8.3
- react-native sdk-34.0.0
- react-native-web 0.11.4
- react-navigation 3.11.0

For a complete list, see the [package.json](https://github.com/reactjsexample/react-native-example-app/blob/master/package.json) file.

---
