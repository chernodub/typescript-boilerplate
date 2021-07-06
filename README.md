# Framework-agnostic typescript boilerplate

No prod dependencies installed 😯

## To install specially-prepared `eslint` configuration (npm 7+ required)

1.  ```bash
    npm i -D @chernodub/eslint-config && echo "{ \"extends\": \"@chernodub/eslint-config\" }" > .eslintrc.json
    ```
2.  Add `"lint": "eslint src/**/*.ts --fix"` to `scripts` in your `package.json`
3.  Run `npm run lint` and chill 🤠
