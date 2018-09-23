# lightscript-minimal-react

A minimal skeleton for a LightScript + React application, ejected from `create-react-app`.

This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app).

# Features

- Powered by Babel 7 and LightScript 4
- Live development server. (`npm start`)
- Full production build, including minification. (`npm run build`)
- Linting with `@lightscript/eslint-plugin`
- Testing with Jest; tests can be written in LightScript.
- GitHub syntax highlighting in `.gitattributes`
- `.editorconfig` for LightScript whitespace mode

# VSCode

While [Visual Studio Code](https://code.visualstudio.com/) is not required to use this package, it has a lot of niceties for working on LightScript code, and comes highly recommended.

If you do use VSCode, installing the following extensions will greatly improve your experience:

- [LightScript syntax](https://marketplace.visualstudio.com/items?itemName=lightscript.lsc)
- [ESLint live linting](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)

We also include some default workplace settings that will live-lint your code as you type in VSCode.

# Commands

## Live Development

```
$ npm start
```

## Building

```
$ npm run build
```

## Testing

```
$ npm test
```

# Notes

- The `package.json` is set to `private`; change that if you wish to publish to NPM.
