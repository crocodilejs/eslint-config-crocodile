
# eslint-config-crocodile

[![Slack Status][slack-image]][slack-url]
[![MIT License][license-image]][license-url]
[![Standard JS Style][standard-image]][standard-url]

> This is an opinionated ESLint configuration for [CrocodileJS][crocodile-url].  It was inspired by [@earnest/eslint-config-es7][earnest-config], but we wanted to make it further opinionated.


## Install

> App:

First add the configuration to your `package.json` file:

```bash
npm i --save-dev eslint-config-crocodile
```

Then create a new file called `.eslintrc`, and its contents should be:

```json
{
  "extends": "crocodile"
}
```

That's it!  Of course you will need to know how to use [ESLint][eslint] from here.

> Tests:

If you need to write tests using `mocha`, you can extend the mocha configuration:

```json
{
  "extends": "crocodile/mocha"
}
```

This adds support for `mocha` environment, and also rules that support `expect`.


## License

[MIT License][license-url]


[license-image]: http://img.shields.io/badge/license-MIT-blue.svg?style=flat
[license-url]: LICENSE
[crocodile-url]: https://crocodilejs.com
[slack-image]: http://slack.crocodilejs.com/badge.svg
[slack-url]: http://slack.crocodilejs.com
[standard-image]: https://img.shields.io/badge/code%20style-standard%2Bes7-brightgreen.svg
[standard-url]: https://github.com/meetearnest/eslint-config-earnest-es7
[unicorn-approved]: http://img.shields.io/badge/unicorn-approved-ff69b4.svg
[unicorn-url]: https://www.youtube.com/watch?v=9auOCbH5Ns4
[eslint]: http://eslint.org/
[earnest-config]: https://github.com/meetearnest/eslint-config-earnest-es7
