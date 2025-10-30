# eslint-config-base

This repository provides a **shared ESLint configuration** for various Onlishop-related projects, ensuring a consistent code style and quality across Onlishop's JavaScript codebases.

## Features

- Shared, standardized ESLint rules for Onlishop projects
- Easy integration into new and existing JavaScript projects
- Promotes consistent code quality and style aligned with Onlishop conventions

## Installation

Install the package via npm:

```
npm install --save-dev @onlishop/eslint-config-base
```

## Usage

After installing, extend the configuration in your project's ESLint config file (e.g., `.eslintrc.js`, `.eslintrc.json`, or `eslint.config.js`):

**.eslintrc.js:**

```
module.exports = {
extends: ['@onlishop/eslint-config-base']
};
```

Refer to [ESLint documentation](https://eslint.org/docs/latest/use/configure/configuration-files) for details on configuration file formats and advanced setup.