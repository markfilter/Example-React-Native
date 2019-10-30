# Example-React-Native
A repository that will be chock full of real-world examples for use in building iOS and Android applications with React Native.

## Development Environment Setup (Mac)
If You have a Windows computer... I am truly sorry.

Open up that amazing program called Terminal and enter the following statements.

```
$ brew update
```
This will update several utility libraries currently on your system.

```
$ brew install node watchman
```
This will install NodeJS and Watchman. React Native uses Watchman to...watch for changes to your project. When changes occur and you save your work, you can freaking hot-load your application on your device or simulator. It's pretty cool.

```
$ npm i -g npm
```
This will upgrade Node Package Manager to the latest version. It's kind of a good idea to do.

```
$ npm i -g react-native-cli
```
This will install the React Native Command-line Interface.

## Starting Your Own React-Native Project

```
$ react-native init <ProjectName>
```

### To Get iOS to Launch

```
$ cd <ProjectName>/ios
$ pod install
$ cd ..
```
Install any pod dependencies that React Native requires.

```
$ react-native run-ios
```
Launch the app.

### To Get Android to Launch
