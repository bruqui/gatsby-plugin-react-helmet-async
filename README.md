# gatsby-plugin-react-helmet-async

[![GitHub](https://img.shields.io/github/license/bruqui/gatsby-plugin-react-helmet-async.svg?style=flat-square)](https://github.com/bruqui/gatsby-plugin-react-helmet-async/blob/master/LICENSE) [![npm (scoped)](https://img.shields.io/npm/v/@bruqui/gatsby-plugin-react-helmet-async.svg?style=flat-square)](https://www.npmjs.com/package/@bruqui/gatsby-plugin-react-helmet-async)

Adds support for [React Helmet Async] to a Gatsby project.

[react helmet async]: (https://github.com/staylor/react-helmet-async)

## Installation

```sh
# Yarn
yarn add react-helmet-async @bruqui/gatsby-plugin-react-helmet-async

# npm
npm install --save react-helmet-async @bruqui/gatsby-plugin-react-helmet-async
```

## Usage

Add the plugin and its options to your `gatsby-config.js` like so:

```js
module.exports = {
  plugins: ["@bruqui/gatsby-plugin-react-helmet-async"]
};
```

Then just use React Helmet Async as you usually would, the plugin will create the `HelmetProvider` component for you and ensure that your `<head>` element contains the correct tags when building your site.
