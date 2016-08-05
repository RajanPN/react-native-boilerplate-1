# React Native Boilerplate

[![Code Climate](https://codeclimate.com/github/multunus/react-native-boilerplate/badges/gpa.svg)](https://codeclimate.com/github/multunus/react-native-boilerplate)
[![Test Coverage](https://codeclimate.com/github/multunus/react-native-boilerplate/badges/coverage.svg)](https://codeclimate.com/github/multunus/react-native-boilerplate/coverage)

> An opinionated boilerplate to setup a iOS/Android app skeleton. Manually configuring a sensible setup is a thing of the past now.

## Features
- Ready for ES2015 and beyond
- Javascript Linting
- Ready for test driven development
- Ready for automated acceptance testing
- Code quality metrics with Code Climate
- Continuous Integration using bitrise.io
- Functional architecture (immutability, hot reloading)
- Form validation
- Code coverage
- Data persistence
- Navigation

## Progress
Initially the boilerplate will support Android only.

- [x] Javascript linting
- [x] Unit Testing setup
- [x] Code coverage
- [x] Redux debugger
- [ ] Continuous Integration setup
- [ ] Automated acceptance testing setup
- [ ] Form validation
- [x] Immutable data structures
- [ ] Hot Reloading
- [ ] Default app structure
- [ ] Navigation
- [x] Persistence

## Libraries
- [React Native](https://facebook.github.io/react-native/)
- [Redux](http://rackt.github.io/redux/)
- [babeljs](https://babeljs.io/)
- [immutablejs](http://facebook.github.io/immutable-js)
- [eslint](http://eslint.org/)
- [mocha](https://mochajs.org/)
- [chai](http://chaijs.com/)
- [sinon](http://sinonjs.org/)
- [Enzyme](http://airbnb.io/enzyme/)
- [nyc](https://github.com/bcoe/nyc)
- And more

## Usage

```
git clone https://github.com/multunus/react-native-boilerplate ReactNativeBoilerplate
cd ReactNativeBoilerplate
npm install
```
Rename ```config.example.json``` to ```config.json``` and modify it as required.

The app is setup to use the [NodeJS JWT Authentication sample server](https://github.com/auth0/nodejs-jwt-authentication-sample), follow the instructions and update the baseURL in ```config.json```.

## Contributing

See the [CONTRIBUTING] document.
Thank you, [contributors]!

  [CONTRIBUTING]: CONTRIBUTING.md
  [contributors]: https://github.com/multunus/react-native-boilerplate/graphs/contributors

## License

React Native Boilerplate is Copyright (c) 2016 Multunus Software Pvt. Ltd.
It is free software, and may be redistributed
under the terms specified in the [LICENSE] file.

  [LICENSE]: /LICENSE

## About

[![Multunus logo](https://s3.amazonaws.com/multunus-images/Multunus_Logo_Vector_resized.png)](http://www.multunus.com/?utm_source=github)

React Native Boilerplate is maintained and funded by Multunus Software Pvt. Ltd.
The names and logos for Multunus are trademarks of Multunus Software Pvt. Ltd.

We love open source software!
See [our other projects][community]
or [hire us][hire] to help build your product.

  [community]: http://www.multunus.com/community?utm_source=github
  [hire]: http://www.multunus.com/contact?utm_source=github
