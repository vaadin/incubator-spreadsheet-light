[![Build Status](https://travis-ci.org/vaadin/incubator-spreadsheet-light.svg?branch=master)](https://travis-ci.org/vaadin/incubator-spreadsheet-light)
[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/vaadin/web-components?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)
[![Published on Vaadin  Directory](https://img.shields.io/badge/Vaadin%20Directory-published-00b4f0.svg)](https://vaadin.com/directory/component/vaadinincubator-spreadsheet-light)
[![Stars in Vaadin_Directory](https://img.shields.io/vaadin-directory/stars/vaadinincubator-spreadsheet-light.svg)](https://vaadin.com/directory/component/vaadinincubator-spreadsheet-light)
[![Latest Version](https://img.shields.io/vaadin-directory/v/vaadinincubator-spreadsheet-light.svg)](https://vaadin.com/directory/component/vaadinincubator-spreadsheet-light)

# &lt;incubator-spreadsheet-light&gt;

[Live Demo ↗](https://incubator.app.fi/incubator-spreadsheet-light-demo/)


[&lt;incubator-spreadsheet-light&gt;](https://vaadin.com/directory/component/vaadinincubator-spreadsheet-light) is a Web Component providing basic functionalities of an spreadsheet.

```html
  <incubator-spreadsheet-light col-count="5" height="700px">
  </incubator-spreadsheet-light>
```

[<img src="https://raw.githubusercontent.com/vaadin/incubator-spreadsheet-light/master/screenshot.png" width="200" alt="Screenshot of incubator-spreadsheet-light">](https://vaadin.com/directory/component/vaadinincubator-spreadsheet-light)


## Installation

The Vaadin Incubator components are distributed as Bower packages.

### Polymer 2 and HTML Imports compatible version

Install `incubator-spreadsheet-light`:

```sh
bower i vaadin/incubator-spreadsheet-light --save
```

Once installed, import it in your application:

```html
<link rel="import" href="bower_components/incubator-spreadsheet-light/incubator-spreadsheet-light.html">
```

## Getting Started

Vaadin components use the Lumo theme by default.

## The file structure for Vaadin components

- `src/incubator-spreadsheet-light.html`

  Unstyled component.

- `theme/lumo/incubator-spreadsheet-light.html`

  Component with Lumo theme.

- `incubator-spreadsheet-light.html`

  Alias for theme/lumo/incubator-spreadsheet-light.html


## Running demos and tests in browser

1. Fork the `incubator-spreadsheet-light` repository and clone it locally.

1. Make sure you have [npm](https://www.npmjs.com/) installed.

1. When in the `incubator-spreadsheet-light` directory, run `npm install` and then `bower install` to install dependencies.

1. Run `polymer serve --open`, browser will automatically open the component API documentation.

1. You can also open demo or in-browser tests by adding **demo** or **test** to the URL, for example:

  - http://127.0.0.1:8080/components/incubator-spreadsheet-light/demo
  - http://127.0.0.1:8080/components/incubator-spreadsheet-light/test


## Running tests from the command line

1. When in the `incubator-spreadsheet-light` directory, run `polymer test`


## Following the coding style

We are using [ESLint](http://eslint.org/) for linting JavaScript code. You can check if your code is following our standards by running `gulp lint`, which will automatically lint all `.js` files as well as JavaScript snippets inside `.html` files.


## Contributing

  - Make sure your code is compliant with our code linters: `gulp lint`
  - Check that tests are passing: `polymer test`
  - [Submit a pull request](https://www.digitalocean.com/community/tutorials/how-to-create-a-pull-request-on-github) with detailed title and description
  - Wait for response from one of Vaadin components team members


## License

Commercial Vaadin Add-on License version 3 (CVALv3). For license terms, see LICENSE.

Vaadin collects development time usage statistics to improve this product. For details and to opt-out, see https://github.com/vaadin/vaadin-usage-statistics.
