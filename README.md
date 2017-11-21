# ESLint config for eth.ly
[![JavaScript Style Guide](https://cdn.rawgit.com/standard/standard/master/badge.svg)](https://github.com/standard/standard)

ESLint-config for standard codestyle, flow, react and jasmine

Config extends the [Standard](https://standardjs.com/) codestyle and adds some
additional rules:

- Recommended rules for [Flow](https://www.npmjs.com/package/eslint-plugin-flowtype#recommended)
- Recommended rules for [React](https://www.npmjs.com/package/eslint-plugin-react#recommended)
- Recommended rules for [Jasmine](https://www.npmjs.com/package/eslint-plugin-jasmine#rules)
- Recommended rules for [Promise](https://www.npmjs.com/package/eslint-plugin-promise#rules)
- Enforcing comma on the end of line
- No weak types for flow

## Usage

Add these lines to your `package.json`:
```json
{
  "eslintConfig": {
    "extends": "ethly"
  },
  "devDependencies": {
    "eslint-config-ethly": "ethly/eslint-config"
  }
}
```
