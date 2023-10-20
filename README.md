# @bricked/ts-template

[![license](https://custom-icon-badges.demolab.com/github/license/brckd/ts-template?logo=law)](LICENSE.md)
[![semantic-release: angular](https://img.shields.io/badge/semantic--release-angular-e10079?logo=semantic-release)](https://github.com/semantic-release/semantic-release)
[![version](https://img.shields.io/npm/v/@bricked/ts-template?color=crimson&logo=npm)](https://www.npmjs.com/package/@bricked/ts-template)

A template for TypeScript projects.

## ToDo

- [ ] [Create](https://github.com/brckd/ts-template/generate) a new repository from this template
- [ ] Find & replace `ts-template` with the name of the new repository
- [ ] Find & replace the description with a proper one
- [ ] Optionally make the [installation guide](#installation) install as `devDependency`

```sh
npm install --save-dev @bricked/ts-template
yarn add --dev @bricked/ts-template
pnpm add --dev @bricked/ts-template
```

- [ ] Add `NPM_TOKEN` as a [new repository secret](https://github.com/brckd/ts-template/settings/secrets/actions/new)
- [ ] Remove `"dryRun": true` from the [`package.json`](./package.json)
- [ ] Remove this section

## Installation

[Node.js](https://nodejs.org/) 16.14.0 or newer is required.

```sh
npm install @bricked/ts-template
yarn add @bricked/ts-template
pnpm add @bricked/ts-template
```

## Usage

`ts-template` can be used as a template for TypeScript projects.

## Building

### Building Publicly

Pulls to the repository will automatically be built with [semantic-release](https://github.com/semantic-release/npm).
The built package can be found on [npm](https://www.npmjs.com/package/@bricked/ts-template?activeTab=code) or in the
[latest github release](https://github.com/brckd/ts-template/releases/latest).

### Building Locally

The package can also be built locally using the `build` script.

```sh
npm run build
yarn run build
pnpm run build
```
