# Welcome to the ReactNativeLibraryProject

The purpose of this app is to create a simple application using react-native-cli to run on an iOS simulator. This is an app intended to be used to learn React Native mobile app development.

## Set Up

This article contains some great steps for setting up your development environment: https://reactnative.dev/docs/environment-setup 

Below are the tools you will need to build the React Native app on your machine:
 - Homebrew
 - Node
 - Watchman

## Running the iOS App

### Command Line Interface

In the command line, at the root of the projet, enter the following:

`npm install` - Install project dependencies

`cd ios` - Switch to ios folder

`pod install` - Install CocoaPods dependencies

`cd ..` - Return to the root folder

`npx react-native start` - Start React Native

`npx react-native run-ios` - Open a separate tab (Command + T) to run the ios app

### Xcode

Alternatively, open `ReactNativeLibraryProject.xcworkspace` using Xcode

Press Play

## Reflections on Approach

From a development perspective, simply getting the development environment set up and app to run takes an extremely long time. The `npx react-native run-ios` command takes several minutes, as well as building the 800+ tasks necessary to build the app from Xcode. Once the project is initially loaded, running the app is fairly quicker, starting up in about 30 seconds. 

