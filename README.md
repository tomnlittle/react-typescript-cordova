# Cordova Typescript React App Boilerplate
![typescript](https://img.shields.io/badge/language-typescript-blue.svg) ![react](https://img.shields.io/badge/language-react-green.svg) ![cordova](https://img.shields.io/badge/language-cordova-lightgrey.svg)

> Cordova Typescript React App

A `simple` :zap: Typescript React App bundled with Cordova to allow you to easily build Apps for Browsers/Android and iOS devices with web development tools that you know and love.

The package uses `create-react-app` and the default configurations that come with that. This should make it easy to upgrade to newer versions of react in the future.

## :books: Table of Contents

- [Installation](#package-installation)
- [Usage](#rocket-usage)
- [Contributing](#memo-contributing)

## :package: Installation

### 1. Prerequisites
- NPM installed
  - **Note: It's recommended to use NPM for this project as Cordova defaults to this manager**
- [Read the Cordova Documentation](https://cordova.apache.org/docs/en/latest/)
- [Cordova installed and setup locally](https://cordova.apache.org/docs/en/latest/)

### 2. Use Cordova's Template Installer
Install the template with the following command:
```sh
cordova create hello com.example.hello HelloWorld --template @tomnlittle/react-typescript-cordova
```

### 3. Install
Once your template has been copied across, move into your new app's folder use `npm` to install all the dependencies.

```sh
ch hello
npm install
```

### 4. Add your target platform
[Cordova Platform Documentation](https://cordova.apache.org/docs/en/10.x/guide/cli/index.html#add-platforms)

Add one or more of the following platforms

**Browser**
```sh
cordova platform add browser
```

**iOS**
```sh
cordova platform add ios
```

**Android**
```sh
cordova platform add android
```

## :rocket: Usage

### Running on your platform
*Run on your platform*
```sh
npm run cordova YOUR_PLATFORM
```

**Example:**
```sh
npm run cordova ios
```

### Running with Create React App
```sh
npm start
```

## :memo: Contributing

Please contribute using [Github Flow](https://guides.github.com/introduction/flow/). Create a branch, add commits, and [open a pull request](https://github.com/tomnlittle/react-typescript-cordova/compare/).
