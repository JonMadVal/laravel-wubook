# laravel-wubook

[![Latest Version on Packagist][ico-version]][link-packagist]
[![Software License][ico-license]](LICENSE.md)
[![Build Status][ico-travis]][link-travis]
[![Coverage Status][ico-scrutinizer]][link-scrutinizer]
[![Quality Score][ico-code-quality]][link-code-quality]
[![Total Downloads][ico-downloads]][link-downloads]

**Note:** Replace ```Filippo Galante``` ```IlGala``` ```http://www.b-ground.com``` ```galante.filippo@b-ground.com``` ```IlGala``` ```laravel-wubook``` ```A WuBook bridge for Laravel 5.x http://wubook.net``` with their correct values in [README.md](README.md), [CHANGELOG.md](CHANGELOG.md), [CONTRIBUTING.md](CONTRIBUTING.md), [LICENSE.md](LICENSE.md) and [composer.json](composer.json) files, then delete this line. You can run `$ php prefill.php` in the command line to make all replacements at once. Delete the file prefill.php as well.

This is where your description should go. Try and limit it to a paragraph or two, and maybe throw in a mention of what
PSRs you support to avoid any confusion with users and contributors.

## Structure

If any of the following are applicable to your project, then the directory structure should follow industry best practises by being named the following.

```
bin/        
config/
src/
tests/
vendor/
```


## Install

Via Composer

``` bash
$ composer require IlGala/laravel-wubook
```

## Usage

``` php
$skeleton = new IlGala\WuBook();
echo $skeleton->echoPhrase('Hello, League!');
```

## Change log

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Testing

``` bash
$ composer test
```

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) and [CONDUCT](CONDUCT.md) for details.

## Security

If you discover any security related issues, please email galante.filippo@b-ground.com instead of using the issue tracker.

## Credits

- [Filippo Galante][link-author]
- [All Contributors][link-contributors]

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

[ico-version]: https://img.shields.io/packagist/v/IlGala/laravel-wubook.svg?style=flat-square
[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square
[ico-travis]: https://img.shields.io/travis/IlGala/laravel-wubook/master.svg?style=flat-square
[ico-scrutinizer]: https://img.shields.io/scrutinizer/coverage/g/IlGala/laravel-wubook.svg?style=flat-square
[ico-code-quality]: https://img.shields.io/scrutinizer/g/IlGala/laravel-wubook.svg?style=flat-square
[ico-downloads]: https://img.shields.io/packagist/dt/IlGala/laravel-wubook.svg?style=flat-square

[link-packagist]: https://packagist.org/packages/IlGala/laravel-wubook
[link-travis]: https://travis-ci.org/IlGala/laravel-wubook
[link-scrutinizer]: https://scrutinizer-ci.com/g/IlGala/laravel-wubook/code-structure
[link-code-quality]: https://scrutinizer-ci.com/g/IlGala/laravel-wubook
[link-downloads]: https://packagist.org/packages/IlGala/laravel-wubook
[link-author]: https://github.com/IlGala
[link-contributors]: ../../contributors