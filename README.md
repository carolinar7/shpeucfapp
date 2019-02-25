# SHPE @ UCF Mobile app Development

Creating an app to facilitate and assist SHPE @ UCF in their daily tasks.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

Java 8 jdk if running an Android Virtual Device (Will not work with higher version as of when this was made) 
```
To check your version open your Command Prompt/Terminal and run 'java -version'
Download here: https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html
You need to set up **Java_Home** if this is your first time running java or have never done it before.
* MacOS - https://dalanzg.github.io/tips-tutorials/mac/2016/03/21/how-to-set-java_home-on-mac-os-x/
* Windows - https://docs.oracle.com/cd/E19182-01/820-7851/inst_cli_jdk_javahome_t/
```
Android Studio to use an Android Virtual Device
```
If you want to run on a physical device follow this: https://facebook.github.io/react-native/docs/running-on-device
Download here: https://developer.android.com/studio
Open up AVD(Android Virtual Device) manager and download an emulator. It doesn't really matter which one
```
XCode version 9.1+
```
You can only download this on **MacOS** through the App store
If you want to use a physical device follow this: https://facebook.github.io/react-native/docs/running-on-device
Make sure you are signed in to your apple account and that your account is a developer account!
```
Node 6
```
MacOS:
* Download HomeBrew here: https://brew.sh/
* On your terminal write: brew install node@6
Windows:
* Download the file that ends with .msi here: https://nodejs.org/dist/v0.6.9/
* If that link doesn't work try looking for the version here https://nodejs.org/dist/
```
Install git to get git command line access
```
Install git here: https://git-scm.com/downloads
```
Install react-native command line interface
```
Open your Terminal/Command Prompt and run: npm i -g react-native-cli
```


### Installing

A step by step series of examples that tell you how to get a development env running

Install the repository
```
open the terminal/Command Prompt and use 'cd /path' to go to a folder. Preferably Desktop
and type: git clone https://github.com/SHPEUCF/shpeucfapp.git
```
Open the folder on the terminal/Command Prompt
```
open the terminal/Command Prompt and type: cd {location of the repo}
```
install all dependencies
```
open the terminal/Command Prompt and type: npm install
```


## Running the app

Running on an Android simulator:
```
Open up Android Studio
Open up the AVD(Android Virtual Device) manager
Run an emulator that you have downloaded already
open the terminal/Command Prompt, go to the repo and type: react-native run-android
```

Running on an iOS simulator:
```
open the terminal/Command Prompt, go to the repo and type: react-native run-ios
```

### Debugging Setup
```
JAVA_HOME missing on:
* MacOS - https://dalanzg.github.io/tips-tutorials/mac/2016/03/21/how-to-set-java_home-on-mac-os-x/
* Windows - https://docs.oracle.com/cd/E19182-01/820-7851/inst_cli_jdk_javahome_t/
ANDROID_HOME missing on:
* MacOS(user2993582) - https://stackoverflow.com/questions/19986214/setting-android-home-enviromental-variable-on-mac-os-x
* Windows(Hoque MD Zahidul) - https://stackoverflow.com/questions/27620262/sdk-location-not-found-define-location-with-sdk-dir-in-the-local-properties-fil
* Print: Entry, ":CFBundleIdentifier", Does Not Exist:
    *UPDATE HERE WITH FIX
```
 

## Deployment

Coming Soon..

## Built With

* [React Native](https://facebook.github.io/react-native/) - The framework used
* [Node](https://nodejs.org/en/) - Package Manager

## Authors

* **Luis Benavides** - *Initial work* - [Github Repo](https://github.com/luisbenan)
* **Haniel Diaz** - *Continued work* - [Github Repo](https://github.com/HanielDiaz)


See also the list of [contributors](https://github.com/SHPEUCF/shpeucfapp/graphs/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
