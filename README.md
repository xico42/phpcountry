# phpcountry

[![Latest Version on Packagist][ico-version]][link-packagist]
[![Software License][ico-license]](LICENSE.md)
[![Build Status][ico-travis]][link-travis]
[![Coverage Status][ico-scrutinizer]][link-scrutinizer]
[![Quality Score][ico-code-quality]][link-code-quality]
[![Total Downloads][ico-downloads]][link-downloads]

**Note:** Replace ```Francisco Edno``` ```fcoedno``` ```https://github.com/fcoedno``` ```ednofco@gmail.com``` ```fcoedno``` ```phpcountry``` ```Provides the ISO databases for the standards 639-3, 3166, 3166-3, 4217 and 15924``` with their correct values in [README.md](README.md), [CHANGELOG.md](CHANGELOG.md), [CONTRIBUTING.md](CONTRIBUTING.md), [LICENSE.md](LICENSE.md) and [composer.json](composer.json) files, then delete this line. You can run `$ php prefill.php` in the command line to make all replacements at once. Delete the file prefill.php as well.

This is where your description should go. Try and limit it to a paragraph or two, and maybe throw in a mention of what
PSRs you support to avoid any confusion with users and contributors.

## Structure

If any of the following are applicable to your project, then the directory structure should follow industry best practices by being named the following.

```
bin/        
build/
docs/
config/
src/
tests/
vendor/
```


## Install

Via Composer

``` bash
$ composer require fcoedno/phpcountry
```

## Usage

``` php
$skeleton = new PHPCountry();
echo $skeleton->echoPhrase('Hello, League!');
```

## Change log

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Testing

``` bash
$ composer test
```

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) and [CODE_OF_CONDUCT](CODE_OF_CONDUCT.md) for details.

## Security

If you discover any security related issues, please email ednofco@gmail.com instead of using the issue tracker.

## Credits

- [Francisco Edno][link-author]
- [All Contributors][link-contributors]

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

[ico-version]: https://img.shields.io/packagist/v/fcoedno/phpcountry.svg?style=flat-square
[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square
[ico-travis]: https://img.shields.io/travis/fcoedno/phpcountry/master.svg?style=flat-square
[ico-scrutinizer]: https://img.shields.io/scrutinizer/coverage/g/fcoedno/phpcountry.svg?style=flat-square
[ico-code-quality]: https://img.shields.io/scrutinizer/g/fcoedno/phpcountry.svg?style=flat-square
[ico-downloads]: https://img.shields.io/packagist/dt/fcoedno/phpcountry.svg?style=flat-square

[link-packagist]: https://packagist.org/packages/fcoedno/phpcountry
[link-travis]: https://travis-ci.org/fcoedno/phpcountry
[link-scrutinizer]: https://scrutinizer-ci.com/g/fcoedno/phpcountry/code-structure
[link-code-quality]: https://scrutinizer-ci.com/g/fcoedno/phpcountry
[link-downloads]: https://packagist.org/packages/fcoedno/phpcountry
[link-author]: https://github.com/fcoedno
[link-contributors]: ../../contributors
