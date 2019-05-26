# react-scripts

This package includes scripts and configuration used by [Create React App](https://github.com/facebook/create-react-app).<br>
Please refer to its documentation:

- [Getting Started](https://facebook.github.io/create-react-app/docs/getting-started) – How to create a new app.
- [User Guide](https://facebook.github.io/create-react-app/) – How to develop apps bootstrapped with Create React App.

## Usage

```shell
npx create-react-app <application name> --scripts-version  git+ssh://git@github.com:miladvafaeifard/custom-react-scripts.git
```

## Development and test proposes

linked it into other local projects in the locally global package:

```shell
npm link
```

your react project in the other place that should be linked to this custom-react-scripts after uninstalling the package:

```shell
npm uninstall custom-react-scripts
```

```shell
npm link custom-react-scripts`
```
