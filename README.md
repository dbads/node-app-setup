## Node-app-setup
  Boilerplate code for setting basic stuff like eslint, typescript, changelog, tests, editor configuration for auto format on save, standard extensions etc. If you are using a framework you might get most of it already setup but not then this may help you a lot.

### Setup

- clone the repo `git clone git@github.com:dbads/node-app-setup.git`
- install dependencies `yarn install`
- you can start building on top of this setup, by default all the code in src folder will be using the configuration, modify paths in ts/es configurations according to your structure

### Features

- Eslint
  App is configured with eslint which uses typescript plugins to work with typescript too
  helps finding syntax styles issues as per rules in eslintrc.js, files in eslintignore are not checked for this

- Prettier
  Basic setup for formating
  files in prettierignore are ignored

- .vscode/settings.json
  contains settings for autoformating and linting fixes on save code action
  `you should install all the extensinos in .vscode/extensions.json for this feature to work`

- CHANGELOG.md
  here you can keep track of changes in app
  use `npm version` to create new versions and the script in .gtihub/scripts/versionCheck.js accordingly move the changes in released section

- Typescript
  `tsconfig.json` defines settings for typescript
  `tsconfig.build.json` defines settings for compilation

- Tests
  to be added


### Want to add something

- add a new pr to `dev` branch, I will review it and merge if looks good.

#### Feel free to reach to me at <a href="mailto:deepakbharti@mnnit.ac.in"> deepakbharti@mnnit.ac.in </a> for any queries.