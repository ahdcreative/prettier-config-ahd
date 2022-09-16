# [@ahdcreative/prettier-config-ahd](https://www.npmjs.com/package/@ahdcreative/prettier-config-ahd)[<img src="https://raw.githubusercontent.com/ahdcreative/prettier-config-ahd/main/.github/prettier-logo.svg?sanitize=true" alt="Prettier" width="90" height="90" align="right">](https://prettier.io)

[![@ahdcreative/prettier-config-ahd on npm](https://img.shields.io/npm/v/@ahdcreative/prettier-config-ahd.svg)](https://www.npmjs.com/package/@ahdcreative/prettier-config-ahd)
[![CI status](https://github.com/ahdcreative/prettier-config-ahd/workflows/CI/badge.svg)](https://github.com/ahdcreative/prettier-config-ahd/actions?query=workflow%3ACI) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> Shareable prettier config, following AHD Creative code style

## Usage

Our default export contains all of our Prettier rules, along with specific plugins for SCSS syntax.

1. Run `npm install prettier @ahdceative/prettier-config-ahd --save-dev`
2. Add `"extends": "@ahdcreative/prettier-config-ahd"` to your `.prettierrc`

### Install

- Required [Node](https://nodejs.org)
- We recommend using [nvm](https://github.com/creationix/nvm)
- Clone the project on to your computer
- Run `nvm install` to ensure you have the correct Node version
- Run `npm install` to install project dependencies
- Ensure your editor is set up to use [editorconfig](https://editorconfig.org/), [Prettier](https://prettier.io/), [Eslint](https://eslint.org/) and [Stylelint](https://stylelint.io/)

### Development

- Run `nvm use` to set Node to the correct version
- Run tests via `npm run test`
- Run linting via `npm run lint`
- Run preflight checks before committing final code via `npm run preflight`
