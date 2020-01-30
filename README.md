<div align="center"># ✏️eslint-config-react-native-dotcode</div>

My eslint configuration for React Native projects. This is my first npm package to help me lint my React Native projects. This has not been tested in production yet so use with caution.

<p align="center">
[![version](https://img.shields.io/github/package-json/v/yarapolana/eslint-config-react-native-dotcode)](https://img.shields.io/github/package-json/v/yarapolana/eslint-config-react-native-dotcode)

[![license](https://img.shields.io/github/license/yarapolana/eslint-config-react-native-dotcode)](https://img.shields.io/github/license/yarapolana/eslint-config-react-native-dotcode)

</p>

## Usage

```
yarn add eslint-config-react-native-dotcode --dev
```

In `.eslintrc`:

```json
{
  "extends": "react-native-dotcode"
}
```

In `babel.config.js` add the following

```json
module.exports = {
  ...
  "plugins": [
    [
      "babel-plugin-root-import", {rootPathSuffix: 'src'},
    ],
  ],
  ...
}
```

# Next step:

Configure CI/CD for version control
