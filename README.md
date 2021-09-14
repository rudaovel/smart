![Tests](https://github.com/dietercoopman/smart/workflows/run-tests/badge.svg)
![Downloads](https://img.shields.io/packagist/dt/dietercoopman/smart.svg?style=flat-square)

# This package makes it possible to create smart images

This packages is very handy if you want to serve private hosted images ( images on a non public path).  It is also very handy if you want to resize your images before sending them 
to the browser.

## Blade component

Smart provides you with a blade component as replacement for the normal `<img>` html tag.  You can pass in all html attributes , they will be applied. 

```html
<x-smart-image src="../storage/file.png" width="400px" />
```

## Installation

You can install the package via composer:

```bash
composer require dietercoopman/smart
```

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Contributing

Please see [CONTRIBUTING](.github/CONTRIBUTING.md) for details.

## Security Vulnerabilities

Please review [our security policy](../../security/policy) on how to report security vulnerabilities.

## Credits

- [Dieter Coopman](https://github.com/dietercoopman)
- [All Contributors](../../contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
