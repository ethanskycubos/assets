# laravel-assets

[![Latest Version on Packagist][ico-version]][link-packagist]
[![Software License][ico-license]](LICENSE.md)
[![Build Status][ico-travis]][link-travis]
[![Coverage Status][ico-scrutinizer]][link-scrutinizer]
[![Quality Score][ico-code-quality]][link-code-quality]
[![Total Downloads][ico-downloads]][link-downloads]


This is where your description should go. Try and limit it to a paragraph or two, and maybe throw in a mention of what
PSRs you support to avoid any confusion with users and contributors.

## Install

Via Composer

``` bash
$ composer require chriscubos/assets
```

### config/app.php
``` php
<?php
return [
    'providers' => [
        Chriscubos\Assets\AssetsServiceProvider::class,
    ],
]
?>
```

### install configuration
``` bash
php artisan vendor:publish
```

### Optional Tasks
``` bash
$ composer dump-autoload
```

## Usage

``` php
// organize collection sets
<?=Assets::collection(['jquery', 'bootstrap', 'style.css']);?>

// grouped packages for your fun
<?=Assets::packages(['colorpicker', 'bootstrap-slider'])?>

// takes assets from the theme folder auto switch with my theme package
<?=Assets::theme(['style.css','_all-skins.min.css'])?>

```

## Configuration



## Change log

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Testing

``` bash
$ composer test
```

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) and [CONDUCT](CONDUCT.md) for details.

## Security

If you discover any security related issues, please email chriscubos@outlook.com instead of using the issue tracker.

## Credits

- [Christopher John Cubos][link-author]
- [All Contributors][link-contributors]

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

[ico-version]: https://img.shields.io/packagist/v/chriscubos/assets.svg?style=flat-square
[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square
[ico-travis]: https://img.shields.io/travis/chriscubos/assets/master.svg?style=flat-square
[ico-scrutinizer]: https://img.shields.io/scrutinizer/coverage/g/chriscubos/assets.svg?style=flat-square
[ico-code-quality]: https://img.shields.io/scrutinizer/g/chriscubos/assets.svg?style=flat-square
[ico-downloads]: https://img.shields.io/packagist/dt/chriscubos/assets.svg?style=flat-square

[link-packagist]: https://packagist.org/packages/chriscubos/assets
[link-travis]: https://travis-ci.org/chriscubos/assets
[link-scrutinizer]: https://scrutinizer-ci.com/g/chriscubos/assets/code-structure
[link-code-quality]: https://scrutinizer-ci.com/g/chriscubos/assets
[link-downloads]: https://packagist.org/packages/chriscubos/assets
[link-author]: https://github.com/chriscubos
[link-contributors]: ../../contributors
