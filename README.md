# `@wizardsoftheweb/modifies-package-root`

[![Build Status](https://travis-ci.org/wizardsoftheweb/modifies-package-root.svg?branch=master)](https://travis-ci.org/wizardsoftheweb/modifies-package-root) [![Coverage Status](https://coveralls.io/repos/github/wizardsoftheweb/modifies-package-root/badge.svg?branch=master)](https://coveralls.io/github/wizardsoftheweb/modifies-package-root?branch=master)

<!-- MarkdownTOC -->

- [Installation](#installation)
    - [Dev version](#devversion)
- [Tests](#tests)
- [Usage](#usage)
- [Scope?](#scope)
- [Roadmap](#roadmap)
    - [Main Features](#mainfeatures)
    - [Eventual features](#eventualfeatures)

<!-- /MarkdownTOC -->


## Installation

<!--
```bash
npm install @wizardsoftheweb/modifies-package-root
```
-->

### Dev version

```
npm install --save git+https://github.com/wizardsoftheweb/modifies-package-root
```

## Tests

```bash
npm t
```

## Usage

TODO: write documentation after the API is done


## Scope?

Polluting the global namespace is generally considered a bad idea, so why would you do it on NPM?

## Roadmap

These percentages are pretty arbitrary. Today's 47% could be tomorrow's 90% or vice versa.

### Main Features

Once all of these are finished, I'll release `v1`. Until then, `v0` should be used with caution, because it's not stable.

| Progess | Feature |
| ------: | ------- |
|      0% | Define `abstract` superclass |
|      0% | Decide on and define concrete API |
|      0% | Create decorator (needs [research](https://www.typescriptlang.org/docs/handbook/decorators.html)) |
|      0% | Create `bin` scripts to build publishable packages |
|      0% | Set up `index` properly |
|      0% | Export the full namespace |
|      0% | Compile declaration file |
|      0% | Compile docs from source |
|      0% | Incorporate `@todo`s somewhere prominent in the docs |
|      0% | Publish package on `npm` |

### Eventual features

These are things I'd like to add, but probably won't be included in `v1`. If not, they'll most likely constitute one or more minor version increments.

| Progess | Feature |
| ------: | ------- |
|      0% | [Greenkeeper](https://greenkeeper.io/) (or similar) integration |
