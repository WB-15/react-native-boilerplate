
🚀 React Native Boilerplate - Jan 2020
===========================================

[![React Native](https://img.shields.io/badge/React%20Native-v0.61.5-green.svg)](https://facebook.github.io/react-native/)
[![React Navigation V3](https://img.shields.io/badge/React%20Navigation-v4.0-blue.svg)](https://reactnavigation.org/)


React Native Boilerplate is a starting point for React Native application. This project is configured with redux, redux saga 
and redux persist. Latest version of react-navigation with NavigationService instead of Redux Integration.

<p float="left">
<a href='http://redux.js.org'><img src='https://camo.githubusercontent.com/f28b5bc7822f1b7bb28a96d8d09e7d79169248fc/687474703a2f2f692e696d6775722e636f6d2f4a65567164514d2e706e67' height='60' alt='Redux Logo' aria-label='redux.js.org' /></a>
 
<a href='https://redux-saga.js.org/'><img src='https://camo.githubusercontent.com/4354872161943c4ae2ceec2a946dec85b96799b8/68747470733a2f2f72656475782d736167612e6a732e6f72672f6c6f676f2f303830302f52656475782d536167612d4c6f676f2d4c616e6473636170652e706e67' height='60' alt='Redux Logo' aria-label='redux-saga.js.org/' /></a>
</p>

## Scalability Factor

This Type based Architecture scales smoothly for small - medium apps. If you guys are building a very large application I would suggest using the following feature based architecture which will be more developer friendly with ease of scaling.

[React-Native-Feature-BoilerPlate](https://github.com/victorkvarghese/react-native-feature-boilerplate)




## Features

* Uses [React Hooks](https://reactjs.org/docs/hooks-intro.html)
* [Redux](http://redux.js.org/) with [hooks](https://react-redux.js.org/api/hooks) support
* [Redux Saga](https://redux-saga.js.org/)
* [Redux Persist](https://github.com/rt2zz/redux-persist/)
* [React Navigation](https://reactnavigation.org/) 
* [React Native Gesture Handler](https://github.com/kmagiera/react-native-gesture-handler) 
* [Jest](https://facebook.github.io/jest/)
* [Eslint](http://eslint.org/) ([Airbnb config](https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb))

## Projects using this BoilerPlate
* [react-native-messenger](https://github.com/victorkvarghese/react-native-messenger)
* [rn-coffee](https://github.com/victorkvarghese/rn-coffee)


## Prerequisites

* [Node](https://nodejs.org) v8.10 (it is recommended to install it via [NVM](https://github.com/creationix/nvm))
* [Yarn](https://yarnpkg.com/)
* A development machine set up for React Native by following [these instructions](https://facebook.github.io/react-native/docs/getting-started.html)

## Getting Started

1. Clone this repo, `git clone https://github.com/victorkvarghese/react-native-boilerplate.git <your project name>`
2. Go to project's root directory, `cd <your project name>`
3. Remove `.git` folder,  `rm -rf .git`
4. Use [React Native Rename](https://github.com/junedomingo/react-native-rename) to update project name `$ npx react-native-rename <newName>`
5. Run `yarn` or `npm install` to install dependencies



11. Start the packager with `npm start`
12. Connect a mobile device to your development machine
13. Run the test application:
  * On Android:
    * Run `react-native run-android`
  * On iOS:
    * Open `ios/YourReactProject.xcodeproj` in Xcode
    * Hit `Run` after selecting the desired device
14. Enjoy!!!


## Contributing

PRs are welcome
