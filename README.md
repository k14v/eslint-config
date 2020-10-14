
# eslint-config-k14v

This package provides the [k14v](https://github.com/k14v) eslint config

# Install

You can install this package with, NPM:

```shell
npm install --save-dev eslint-config-k14v
```

or with Yarn:
```shell
yarn add eslint-config-k14v --dev
```

## Peer Depencencies

This package don't have any package as dependency, all it have is `peerDependencies`. You can install only what it's needed.

#### Install all `peerDependencies`

```shell
npx install-peerdeps eslint-config-k14v --dev
```

#### Install `peerDependencies` just for javascript

NPM:

```shell
npm install --save-dev eslint eslint-plugin-import babel-eslint
```

Yarn:

```shell
yarn eslint eslint-plugin-import babel-eslint --dev
```

# Usage

Open your `.eslintrc` configuration file and add the following:

```javascript
  "extends": [ "eslint-config-k14v" ],
```

If you want the React rules, use:

```javascript
  "extends": [ "eslint-config-k14v/lib/react" ]
```

React rules extends the base rules. So, you will have both.

In the end your `.eslintrc` file will look something like:

```javascript
module.exports = {
  "extends": [ "eslint-config-k14v" ],
  "rules": {},
}
```

## Override rules

The rules in this config can be overriden setting your own rules in your `.eslintrc` config file.
