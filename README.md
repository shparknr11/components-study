# npx create-react-app ./

# npm i @emotion/react

# npm i @emotion/styled

# .prettierrc.json 파일 생성 후 text 붙혀넣기

```text
 {
  "singleQuote": false,
  "semi": true,
  "useTabs": false,
  "tabWidth": 2,
  "trailingComma": "all",
  "printWidth": 80,
  "arrowParens": "avoid",
  "endOfLine": "auto"
}
```

# npm install eslint-config-react-app --save-dev

# npx eslint --init

# npm i eslint --dev

# npm install eslint-config-prettier --save-dev

# .eslintrc.js 파일에 붙혀넣기

```text
extends: [
    "eslint:recommended",
    "plugin:react/recommended",
    "prettier"
],
```

```text
rules: {
  "react/react-in-jsx-scope": "off",
  "react/prop-types": "off",
  "no-unused-vars": "off",
},
```

- 복사후 내용

```text
module.exports = {
  env: {
    browser: true,
    es2021: true,
  },
  extends: ["eslint:recommended", "plugin:react/recommended", "prettier"],
  overrides: [
    {
      env: {
        node: true,
      },
      files: [".eslintrc.{js,cjs}"],
      parserOptions: {
        sourceType: "script",
      },
    },
  ],
  parserOptions: {
    ecmaVersion: "latest",
    sourceType: "module",
  },
  plugins: ["react"],
  rules: {
    "react/react-in-jsx-scope": "off",
    "react/prop-types": "off",
    "no-unused-vars": "off",
  },
};
```

# npm install @babel/plugin-proposal-private-property-in-object --dev

# npm i axios
