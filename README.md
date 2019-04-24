## Stylelint configuration

This is a personal Stylelint configuration.

## Install

```bash
npm i @aszydelko/stylelint-config --save-dev
```

## Usage

This config is designed to work with the `extends` feature of `.stylelintrc` files.

Then, add this to your `.stylelintrc` or `package.json` file:

```
{
  "extends": "@aszydelko/stylelint-config"
}
```

You can override settings from this config by adding them directly into your
`.eslintrc` or `package.json` file.

#### Commands

Recommended set of commands to put in `package.json` scripts:

```
  "lint:css": "stylelint ./**/*.css ./**/*.scss ./**/*.vue",
  "lint-autofix:css": "stylelint ./**/*.css ./**/*.scss ./**/*.vue --fix",
```

## License

MIT Copyright (c) Arkadiusz Szydełko
