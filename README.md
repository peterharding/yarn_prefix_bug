### Setup
1. Install `nvm` - https://github.com/creationix/nvm
2. Install `yarn` - https://yarnpkg.com/lang/en/docs/install/

### Use
1. `npm run example` = see that there is no error
2. `yarn run example` = see error:
```
nvm is not compatible with the "PREFIX" environment variable: currently set to "/usr/local"
Run `unset PREFIX` to unset it.
```

### Log files
terminal.env.log = `env` from terminal
npm.env.log = `env` from `npm run example`
yarn.env.log = `env` from yarn run example
