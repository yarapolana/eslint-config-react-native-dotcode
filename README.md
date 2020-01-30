<h1 align="center"> ✏️eslint-config-react-native-dotcode </h1>
<h3 align="center">Eslint configuration for React Native projects</h3>


<p align="center">

<img src="https://img.shields.io/github/package-json/v/yarapolana/eslint-config-react-native-dotcode.svg">
<img src="https://img.shields.io/github/license/yarapolana/eslint-config-react-native-dotcode.svg">

</p>

<p>This is my first npm package to help lint React Native projects.</p>


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
  "..."
  "plugins": [
    [
      "babel-plugin-root-import", {"rootPathSuffix": "src"},
    ],
  ],
  "..."
}
```

### Next step:

Configure CI/CD for version control


### Authors:

<p>
  <a href="https://github.com/yarapolana">
    <img src="https://avatars0.githubusercontent.com/u/19730118?s=460&v=4" width="50" height="50">
  </a>
  <a href="https://dotcode.is">
    <img src="https://avatars0.githubusercontent.com/u/19730118?s=460&v=4" width="50" height="50">
  </a>
</p>
