webconsole-cli
==============

Composer package that provides a command-line interface to
[Nickolay Kovalev's Web Console](http://web-console.org/).

[![Latest Stable Version](https://img.shields.io/packagist/v/amercier/webconsole-cli.svg)](https://packagist.org/packages/amercier/webconsole-cli)
[![PHP version](https://img.shields.io/packagist/php-v/amercier/webconsole-cli.svg)](https://packagist.org/packages/amercier/webconsole-cli)
[![License](https://img.shields.io/packagist/l/amercier/webconsole-cli.svg)](https://packagist.org/packages/amercier/webconsole-cli)

Requirements
------------

- [Webconsole](http://web-console.org/) instance running
- [PHP](http://php.net/) >= 5
- [Composer](https://getcomposer.org/)


Installation
------------

```bash
composer require amercier/webconsole-cli
```

**Note:** _Webconsole_ is not installed as a dependency, you need to have an instance running elsewhere.


Usage
-----

```bash
vendor/bin/webconsole -u jsmith -p 123456 https://webremote.example.com 'ls -Al'
```

**Note:** run `vendor/bin/webconsole --help` for more options and details.


Contributing
------------
Contributions (issues ♥, pull requests ♥♥♥) are more than welcome! Feel free to
clone, fork, modify, extend, etc, as long as you respect the
[ISC License](license terms).


License
-------

This project is released under [ISC License](LICENSE.md) license.
