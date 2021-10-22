<h1 align="center" style="border-bottom: none;">🛠️ css-library-example</h1>
<h3 align="center">Example CSS Library with Storybook</h3>

**css-library-example** is an example of how to build a CSS library with an accompanying [Storybook].

## Development Guide

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

[Storybook]: https://storybook.js.org/
[Dart Sass]: https://sass-lang.com/dart-sass
[PostCSS]: https://postcss.org/
[Autoprefixer]: https://github.com/postcss/autoprefixer
[clean-css]: https://github.com/clean-css/clean-css-cli
