# ESlint Config

These are settings for eslint and prettier.

## Usage

Create a `.eslintrc.yaml` file in your project and add the following content:

```text
root: true
extends:
  - "@yellowgarbagegroup/eslint-config/.eslintrc.yaml"
```

To use prettier add the following line in your `package.json`

```text
"prettier": "@yellowgarbagegroup/eslint-config"
```

Add this package to your project:

```bash
pnpm add @yellowgarbagegroup/eslint-config -D
```