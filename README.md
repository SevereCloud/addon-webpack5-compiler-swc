# @storybook/addon-webpack5-compiler-swc

This addon adds SWC support to Storybook's webpack5 compiler. It adds the swc-loader to the webpack config and sets the `swc-loader` as the default loader for JavaScript and TypeScript files.

## Installation

```sh
npm install --save-dev @storybook/addon-webpack5-compiler-swc
```

## Usage

```js
// .storybook/main.js

const config = {
  addons: ["@storybook/addon-webpack5-compiler-swc"],
};

export default config;
```

## Configuration

Please go to https://storybook.js.org/docs/api/main-config-swc#swcoptions for more information about how to configure SWC.
