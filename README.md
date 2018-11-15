# eslint-config-ufhealth

A shareable eslint config for UF Health projects.

Extends [standard](https://github.com/standard/eslint-config-standard), and includes the [only-warn](https://github.com/bfanger/eslint-plugin-only-warn) plugin so eslint will just yell at you for bad code, not prevent you from compiling it.

## Install

```bash
yarn add -D eslint-config-ufhealth
```

## Usage

[Shareable configs](http://eslint.org/docs/developer-guide/shareable-configs) are designed for use with the `extends` option of your `.eslintrc`. After installing, just add this to your `.eslintrc` file:

```json
{
  "extends": "ufhealth"
}
```

That's basically it. Override any settings you want from this configuration by just adding them directly to your `.eslintrc` file.

## Changelog

The [commit log](https://github.com/ufhealth/eslint-config-ufhealth/commits/master) should be pretty readable. If it isn't, please yell at us.
