# Export locals only css-loader setting and mini-css-extract-plugin

This repository contains a minimum reproducible test case for an error
encountered while using `css-loader` and `mini-css-extract-plugin`.

## Getting started

Install dependencies.

```bash
yarn install
```

Start server.

```
webpack serve
```

Resulting error:

```bash
TypeError: Cannot use 'in' operator to search for 'locals' in undefined
```
