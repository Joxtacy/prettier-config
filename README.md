# @joxtacy/prettier-config

My preferred code formatting rules.

## Installation

To install this package run the following command in the terminal in the root directory of your application.

```
npm install --save-dev @joxtacy/prettier-config
```

**OR**

```
yarn add --dev @joxtacy/prettier-config
```

## Usage

Add a key in your **package.json** file.

```
"prettier": "@joxtacy/prettier-config"
```

**OR**

Create a **.prettierrc** , **.prettierrc.json**, **.prettierrc.yml**, **.prettierrc.yaml** or, **.prettierrc.json5** file and export a string.

```
"@joxtacy/prettier-config"
```

**OR**

If you want to extend the configuration or overwrite some settings, create a **prettier.config.js** or **.prettierrc.js** file and export an object.

```
module.exports = {
  ...require("@joxtacy/prettier-config"),
  semi: false,
};
```
