<h1 align="center" style="border-bottom: none;">🛠️ css-library-example</h1>
<h3 align="center">Example CSS Library with Storybook</h3>

<div align="center">
    <a href="https://www.npmjs.com/package/@topplethenun/css-library-example">
        <img alt="npm (scoped)" src="https://img.shields.io/npm/v/@topplethenun/css-library-example">
    </a>
    <a href="https://github.com/intuit/auto">
        <img alt="Auto Release" src="https://img.shields.io/badge/release-auto.svg?colorA=888888&colorB=9B065A&label=auto">
    </a>
</div>

**css-library-example** is an example of how to build a CSS library with an accompanying [Storybook].

It is not intended for any real use.

## Installation

If you'd still like to install **css-library-example** anyway, you can do so by following one of the below sections.

### npm / yarn

You can install it by running one of the below in your terminal:

```shell
npm install @topplethenun/css-library-example
```

or

```shell
yarn add @topplethenun/css-library-example
```

### unpkg

You can install it by adding the below to the `<head>` section of your HTML:

```html
<link
  rel="stylesheet"
  href="https://unpkg.com/@topplethenun/css-library-example/dist/css-library-example.min.css"
/>
```

## Contributing

### Prerequisites

- NodeJS >= 12
- [Yarn](https://yarnpkg.com/)

### Building

Code is built using [Dart Sass], then [PostCSS] with [Autoprefixer], then [clean-css]. You can build the library by
running the below from your terminal:

```shell
$ yarn build
```

### Storybook

You can run the Storybook instance for this library by running the below from your terminal and then following
the instructions presented:

```shell
yarn storybook
```

### Code Formatting

Code should be formatted following the Prettier code style. You can reformat the code automatically by running the below
from your terminal:

```shell
$ yarn format
```

[storybook]: https://storybook.js.org/
[dart sass]: https://sass-lang.com/dart-sass
[postcss]: https://postcss.org/
[autoprefixer]: https://github.com/postcss/autoprefixer
[clean-css]: https://github.com/clean-css/clean-css-cli

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://richardharrah.com/"><img src="https://avatars.githubusercontent.com/u/1672786?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Richard Harrah</b></sub></a><br /><a href="#example-ToppleTheNun" title="Examples">💡</a> <a href="https://github.com/ToppleTheNun/css-library-example/commits?author=ToppleTheNun" title="Code">💻</a> <a href="https://github.com/ToppleTheNun/css-library-example/commits?author=ToppleTheNun" title="Documentation">📖</a> <a href="#infra-ToppleTheNun" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a></td>
  </tr>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!
