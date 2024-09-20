# A Color Bright's browserslist config

## Introduction

Our standard level of browser support includes:
- The `defaults` query [recommended by Browserlist](https://github.com/browserslist/browserslist?tab=readme-ov-file#best-practices)
- The NextJS [supported browser list](https://nextjs.org/docs/architecture/supported-browsers)

## Installation

Via npm:

```
npm install --save-dev acolorbright/browserslist-config#v2.0.0
```

## Usage

Add the following to your `package.json`:

```
"browserslist": [
  "extends @acolorbright/browserslist-config"
]
```

Or, create a `.browserslistrc` file with the following contents:

```
extends @acolorbright/browserslist-config
```
