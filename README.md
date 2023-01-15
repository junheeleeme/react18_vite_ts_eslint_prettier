# react18_ts_eslint_prettier_boilerplate

<br/>

## 🧑🏻‍💻 Install

```
yarn add -D eslint prettier airbnb eslint-config-airbnb eslint-config-airbnb-typescript eslint-config-prettier eslint-plugin-import eslint-plugin-jsx-a11y eslint-plugin-prettier eslint-plugin-react eslint-plugin-react-hooks
```

<br/>

## 🎉 .eslintrc

```
{
  "env": {
    "browser": true,
    "es2021": true
  },
  "extends": ["airbnb", "airbnb-typescript", "airbnb/hooks", "plugin:react/recommended", "plugin:@typescript-eslint/recommended", "plugin:prettier/recommended"],
  "overrides": [],
  "parser": "@typescript-eslint/parser",
  "parserOptions": {
    "ecmaVersion": "latest",
    "sourceType": "module",
    "project": "./tsconfig.json"
  },
  "plugins": ["react", "@typescript-eslint", "prettier"],
  "rules": {
    "react/react-in-jsx-scope": 0,
    "react/jsx-filename-extension": [1, { "extensions": [".ts", ".tsx"] }],
    "react/function-component-definition": [
      2,
      {
        "namedComponents": "arrow-function",
        "unnamedComponents": "arrow-function"
      }
    ],
    "prettier/prettier": ["error", { "endOfLine": "auto" }],
    "import/prefer-default-export": "off",
    "default-param-last": "off",
    "no-console": "off",
    "import/no-cycle": "off",
    "import/no-unresolved": "off", // webpack alias
    "dot-notation": "off",
    "no-alert": "off",
    "import/extensions": "off"
  }
}
```

<br>

## 🎉 .prettier

```
{
  "printWidth": 200,
  "tabWidth": 2,
  "singleQuote": true,
  "tranilingComma": "all",
  "semi": false
}
```
