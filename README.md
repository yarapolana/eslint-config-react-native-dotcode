# ✏️eslint-config-react-native-dotcode

My eslint configuration for React Native projects. I created this package to test npm package creation. Use with caution.

[![version](https://img.shields.io/github/package-json/v/yarapolana/eslint-config-react-native-dotcode)](https://img.shields.io/github/package-json/v/yarapolana/eslint-config-react-native-dotcode)

[![license](https://img.shields.io/github/license/yarapolana/eslint-config-react-native-dotcode)](https://img.shields.io/github/license/yarapolana/eslint-config-react-native-dotcode)

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
