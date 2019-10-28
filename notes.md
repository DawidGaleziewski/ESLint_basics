# Linting - program that will analyze the code

# Airbnb style guide:

https://github.com/airbnb/javascript

# We can install the style guide package in order to better our code:

eslint-config-airbnb

## Installing the airbnb style guide ESlint

npx install-peerdeeps --dev eslint-config-airbnb

# use Prettier for formatting

#install dev dependencies in the project:
npm i -D eslint prettier eslint-plugin-prettier eslint-config-pretier eslint-plugin-node eslint-config-node

sudi i -g npx

npx ins
tall-peerdeps --dev eslint-config-airbnb

## config for prettier needs to be in .prettierrc file

We write the config in json file.
more options for prettier can be found in:
https://prettier.io/docs/en/options.html

## config for eslint can be created manually or installed globally and then generated:

sudo npm i -g eslint
eslint --init #this will ask some questions on the config

This installs eslint and creates config for it in .eslintrc.js

## we need to mod our .eslintrc.js

module.exports = {
extends: ['airbnb', 'prettier'],
plugins: ['prettier'],
rules: {}
};
