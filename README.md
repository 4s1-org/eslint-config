# ESlint Config

These are settings for [ESLint](https://eslint.org/) and [Prettier](https://prettier.io/).

## Install

Add this package to your project:

```bash
# pnpm
pnpm add prettier @4s1/eslint-config -D
# npm
npm install prettier @4s1/eslint-config -D
```

Create a `.eslintrc.yaml` file in your project root folder and add the following content:

```text
root: true
extends:
  - "@4s1/eslint-config/.eslintrc.yaml"
```

To use prettier add the following line into your `package.json`

```text
"prettier": "@4s1/eslint-config"
```
