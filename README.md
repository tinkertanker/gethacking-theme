[![Build Status](https://travis-ci.org/Shopify/starter-theme.svg?branch=master)](https://travis-ci.org/Shopify/starter-theme)

## System requirements

- **Node:** The current LTS (long-term support) release. We like to use a Node Version Manager like [NVM](https://github.com/creationix/nvm).

- **NPM 5+ or Yarn:** Both of these package managers have [ups and downs](https://blog.risingstack.com/yarn-vs-npm-node-js-package-managers/), choose whichever you prefer. Follow the installation instructions [for Yarn](https://yarnpkg.com/en/docs/install) or [NPM](https://www.npmjs.com/get-npm) to make sure you're using the latest version.

## Getting started

1. Create a theme folder
```
$ yarn create slate-theme <name of local folder> //OR
$ npx create-slate-theme my-new-theme
```

2. Follow the steps in https://shopify.github.io/slate/docs/connect-to-your-store to update the .env file. The slate_theme_id has to be retrieved from the current live theme.

3. Pull the files from this repo into the src folder.

4. Edit the theme as you like on your text editor.

5. To preview your theme:
```
$ yarn start //OR
$ npm start
```

6. To deploy the editted theme to the shopify app:
```
$ yarn deploy //OR
$ npm run deploy
```



For more information on connecting your new project with a Shopify store, see the [Slate docs](https://github.com/Shopify/slate/wiki/3.-Connect-to-your-store).

## Contributing

For help on setting up the repository locally, building, testing, and contributing
please see [CONTRIBUTING.md](https://github.com/Shopify/starter-theme/blob/master/CONTRIBUTING.md).

## Code of Conduct

All developers who wish to contribute through code or issues, take a look at the
[Code of Conduct](https://github.com/Shopify/starter-theme/blob/master/CODE_OF_CONDUCT.md).

## License

Copyright © 2018 Shopify. See [LICENSE](https://github.com/Shopify/starter-theme/blob/master/LICENSE) for further details.
