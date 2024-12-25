# cra-template-typescript-blank

This is a TypeScript template for [Create React App](https://github.com/facebook/create-react-app) which is entirely blank.

No spinning logo, no unnecessary boilerplate code.

In addition to [the official TypeScript template](https://github.com/facebook/create-react-app/tree/main/packages/cra-template-typescript), the following dependencies are included by default:

- [`classnames`](https://www.npmjs.com/package/classnames)
- [`eslint-plugin-jsx-a11y`](https://www.npmjs.com/package/eslint-plugin-jsx-a11y)
- [`eslint-plugin-sonarjs`](https://www.npmjs.com/package/eslint-plugin-sonarjs)
- [`prettier`](https://www.npmjs.com/package/prettier)
- [`react-router-dom`](https://www.npmjs.com/package/react-router-dom)
- [`stylelint`](https://www.npmjs.com/package/stylelint)
- [`stylelint-config-standard`](https://www.npmjs.com/package/stylelint-config-standard)
- [`stylelint-prettier`](https://www.npmjs.com/package/stylelint-prettier)

Furthermore, there are the following additions:

- HTTPS is enabled in development and test mode
- Some additional npm scripts are available:
  - `npm run lint-js` to run ESLint
  - `npm run lint-css` to run Stylelint
  - `npm run lint` to run both ESLint and Stylelint
  - `npm run prettier` to run a Prettier check
- A GitHub actions workflow is available that runs build, test, and linters on pull requests
- ESLint configuration is extended to include recommended rules from:
  - `eslint-plugin-jsx-a11y`
  - `eslint-plugin-sonarjs`

To use this template, add `--template typescript-blank` when creating a new app.

For example:

```sh
npx create-react-app my-app --template typescript-blank

# or

yarn create react-app my-app --template typescript-blank
```

For more information, please refer to:

- [Getting Started](https://create-react-app.dev/docs/getting-started) – How to create a new app.
- [User Guide](https://create-react-app.dev) – How to develop apps bootstrapped with Create React App.
