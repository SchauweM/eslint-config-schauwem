# eslint-config-schauwem

:wrench: This is my personal eslint configuration.

## Installation

Install this package and save it as a devDependency:

```
yarn add eslint-config-schauwem --dev
```

or via npm if you swing that way:

```
npm i -D eslint-config-schauwem
```

Then have your project's `.eslintrc` file extend the ruleset.

```json
{
  "extends": "schauwem"
}
```

If you're using React in your project:

```json
{
  "extends": "schauwem/react"
}
```

## License

The MIT License (MIT). Please see [License File](LICENSE) for more information.
This configuration is a stand-alone modified fork from [@devinehowest eslint-devine](https://github.com/devinehowest/eslint-config-devine)
