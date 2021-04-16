# ESlint Config

These are settings for eslint and prettier.

## Usage

Create a `.eslintrc.yaml` file in your project and add the following content:

```text
root: true
extends:
  - "@hest-lab/eslint-config/.eslintrc.yaml"
```

To use prettier add the following line in your `package.json`

```text
"prettier": "@hest-lab/eslint-config"
```
