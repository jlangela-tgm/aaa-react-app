# Soccer Wizard

Soccer Wizard is a Web app that displays several soccer clubs and ranks them either by their name or value.

The user can click on one of the Clubs to be redirected to a page containing further information

## Features

The app contains two noteworthy features, the first one being sorting and the second one being translating.

### Sorting

The ListView page of the app, contains a sorting button that toggles between sorting the list by the clubs names and sorting the list by the clubs value.

### Translation

Both Pages contain a button for switching the Apps language from German to English and vice versa.

## Template

This project was bootstrapped through `yarn create react-app my-app --scripts-version=aaa-react-scripts-ts`, a customized react template project generator for [at all about apps](https://allaboutapps.at).

## Additional dependencies

- [`material-ui`](https://npmjs.org/package/material-ui)
- [`react-intl`](https://npmjs.org/package/react-intl)
  - A custom `@types/react-intl` is supplied in generated projects that introduces the generic IDS to check used i18n keys during compile time
- [`intl`](https://npmjs.org/package/intl) (Polyfill for safari, only loaded if required)
- [`lodash`](https://npmjs.org/package/lodash)
- [`hoist-non-react-statics`](https://npmjs.org/package/hoist-non-react-statics) (If you write your own Higher Order Components)
- [`formik`](https://github.com/jaredpalmer/formik)
- [`yup`](https://github.com/jquense/yup) (as validator for formik)
- [`mobx`](https://npmjs.org/package/mobx) + [`mobx-react`](https://npmjs.org/package/mobx-react) + [`mobx-persist`](https://npmjs.org/package/mobx-persist) + [`localforage`](https://npmjs.org/package/localforage)
- [`react-router`](https://npmjs.org/package/react-router)
- [`apollo-client`](https://npmjs.org/package/apollo-client) + [`graphql-tag`](https://npmjs.org/package/graphql-tag) + [`apollo-cli`](https://www.npmjs.com/package/apollo)

## Original READMEs

[Create React App](https://github.com/facebookincubator/create-react-app).

The most recent version of the Create React App guides can be found [here](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md).
