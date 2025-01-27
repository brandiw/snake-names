# [snake-names](https://github.com/murshidazher/snake-names)  [![npm](https://img.shields.io/npm/v/snake-names.svg?label=&color=0080FF)](https://github.com/murshidazher/snake-names/releases/tag/v1.0.0)


[![travisci](https://img.shields.io/travis/com/murshidazher/snake-names/master?style=flat-square)](https://travis-ci.com/)
[![codecov](https://img.shields.io/codecov/c/gh/murshidazher/snake-names/master?logo=codecov&style=flat-square&token=L8FWILY45J)](https://codecov.io/gh/murshidazher/snake-names)
![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)


> Get popular snake names. Certified Lit 🔥🔥 __Accepting PRs for additional names.__

- A npm package to return a list of popular snake names.

## Table of Contents

  - [Table of Contents](#table-of-contents)
  - [Installing / Getting started](#installing--getting-started)
  - [Usage](#usage)
  - [CLI](#cli)
  - [API](#api)
  - [License](#license)

## Installing / Getting started

A quick introduction of the minimal setup you need to get a up & running.

```shell
$ npm install snake-names
```

## Usage

Here's a brief intro about what a developer must do in order to start developing the project further:

```js
const snakeNames = require('snake-names');

snakeNames.random();
//=> 'Albert'
```

## CLI

```
$ npm install --global snake-names
```

```
$ snake-names --help

  Get popular snake names

  Usage
    $ snake-names

  Options
    --all   Get all the names instead of a random name
    --type  Type of name  [Default: all]  [Values: female, male, all]

  Examples
    $ snake-names
    Albert
    $ snake-names --all --type male
    Adrian
    Igor
    …
```

## API

|       Method      |     Type     | Description                                                                                                             |
|:-----------------:|:------------:|-------------------------------------------------------------------------------------------------------------------------|
|  `.all`       |     array    | List all popular snake names                                                                                            |
|  `.male`      |     array    | List all popular male snake names                                                                                       |
|  `.female`    |     array    | List all popular female snake names                                                                                     |
|  `.cute`      |     array    | List all cute snake names                                                                                               |
|  `.unique`    |     array    | List all unique snake names                                                                                             |
|  `.famous`    |     array    | List all famous snake names                                                                                             |
|  `.random(n)` | string/array | returns a random snake name if no param is provided.  Otherwise, returns an array of random snake names of length  `n`. |

## License

[MIT](https://github.com/murshidazher/snake-names/blob/master/LICENSE) © Murshid Azher.