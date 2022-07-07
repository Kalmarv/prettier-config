# @kalmarv/prettier-config

<p align="center">
  <a href="https://github.com/Kalmarv/prettier-config/blob/main/LICENSE">
    <img alt="license" src="https://badgen.net/github/license/kalmarv/prettier-config">
  </a>
   <a href="https://www.npmjs.com/package/@kalmarv/prettier-config">
    <img alt="version" src="https://badgen.net/npm/v/@kalmarv/prettier-config">
  </a>
</p>

Personal [Prettier](https://prettier.io/)
[config](https://prettier.io/docs/en/configuration.html).

## Installation

```shell
npm i -D @kalmarv/prettier-config
```

## Usage

Reference `@kalmarv/prettier-config` in your `package.json`:

```json
{
  "prettier": "@kalmarv/prettier-config"
}
```

Or extend the configuration using .prettierrc.js:

```js
module.exports = {
  ...require('@kalmarv/prettier-config'),
  plugins: ['prettier-plugin-foo'],
}
```

## License

[MIT][license]

[license]: ./LICENSE
