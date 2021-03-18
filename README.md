# Frontend part of [apix.trade](apix.trade "Project link")

## Project setup
You will need installed [node.js](https://nodejs.org/en/) and [yarn](https://yarnpkg.com/getting-started/install)

Run `yarn` for init the project

### Compile and start hot-reloads server for development
`yarn gulp`

### Compile and minify for production
`yarn gulp build`

### Create critical styles for pages
`yarn gulp critical`

### Configs

`gulpfile.js` is script of gulp bundler. Also you can define environment variables there.

`.editorconfig` uses for [EditorConfig](https://editorconfig.org/) plugin.
Please install it in your editor before changing this code.

`.eslintrc` is config for [ES Lint](https://eslint.org/) for control correctness of your code style.

`.babelrc` is config for [Babel](https://babeljs.io/).

