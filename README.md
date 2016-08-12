# phpunit-completions

[![Author](https://img.shields.io/badge/author-@gerardroche-blue.svg?style=flat)](https://twitter.com/gerardroche)
[![Source Code](https://img.shields.io/badge/source-GitHub-blue.svg?style=flat)](https://github.com/gerardroche/sublime-phpunit-completions)
[![License](https://img.shields.io/badge/license-BSD--3-blue.svg?style=flat)](https://raw.githubusercontent.com/gerardroche/sublime-phpunit-completions/master/LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/gerardroche/sublime-phpunit-completions.svg?style=flat)](https://github.com/gerardroche/sublime-phpunit-completions/stargazers)

[![Sublime version](https://img.shields.io/badge/sublime-v2|v3-lightgrey.svg?style=flat)](https://sublimetext.com)
[![Latest version](https://img.shields.io/github/tag/gerardroche/sublime-phpunit-completions.svg?label=release&style=flat&maxAge=2592000)](https://github.com/gerardroche/sublime-phpunit-completions/tags)
[![Downloads](https://img.shields.io/packagecontrol/dt/phpunit-completions.svg?style=flat&maxAge=2592000)](https://packagecontrol.io/packages/phpunit-completions)

PHPUnit completions for Sublime Text.

Works best with [PHP Grammar], [PHP Completions], [PHP Snippets], [PHPUnit], and [PHPUnit Snippets].

## Overview

* [Features](#features)
* [Key Bindings](#key-bindings)
* [Installation](#installation)
* [Contributing](#contributing)
* [Changelog](#changelog)
* [License](#license)

# Features

* PHPUnit [~5.4](http://semver.org)
* DbUnit [~2.0](http://semver.org)
* [PSR](http://www.php-fig.org) compliant
* Scoped to minimise auto-complete noise
* Test case type hints e.g. begin typing at `class Name extends |` and any other context where a type hint is valid.
* [Assertions](https://phpunit.de/manual/current/en/appendixes.assertions.html) e.g. begin typing `assert|` or `$this->assert|`
* Test case helpers e.g. begin typing `getMockBuilder|` or `$this->getMockBuilder|`
* [Annotations](https://phpunit.de/manual/current/en/appendixes.annotations.html) e.g. begin typing _(any valid doc block scope)_ `/* @covers| */` or without the `@` symbol `/* covers| */`

## Key Bindings

| OS X | Windows | Linux | Description |
|------|---------|-------|-------------|
| <kbd>Ctrl</kbd>+<kbd>Space</kbd> | <kbd>Ctrl</kbd>+<kbd>Space</kbd> | <kbd>Alt</kbd>+<kbd>/</kbd> | Activate completions |

To enable [tab-completions](http://docs.sublimetext.info/en/latest/extensibility/completions.html#tab-completed-completions) set `"tab_completion": true` in `Preferences > Settings - User`.

## Installation

### Manual installation

1. Close Sublime Text.
2. Download or clone this repository to a directory named `phpunit-completions` in the Sublime Text Packages directory for your platform:
    * Sublime Text 3
        - Linux: `git clone https://github.com/gerardroche/sublime-phpunit-completions.git ~/.config/sublime-text-3/Packages/phpunit-completions`
        - OS X: `git clone https://github.com/gerardroche/sublime-phpunit-completions.git ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/phpunit-completions`
        - Windows: `git clone https://github.com/gerardroche/sublime-phpunit-completions.git %APPDATA%\Sublime/ Text/ 3/Packages/phpunit-completions`
    * Sublime Text 2
        - Linux: `git clone https://github.com/gerardroche/sublime-phpunit-completions.git ~/.config/sublime-text-2/Packages/phpunit-completions`
        - OS X: `git clone https://github.com/gerardroche/sublime-phpunit-completions.git ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/phpunit-completions`
        - Windows: `git clone https://github.com/gerardroche/sublime-phpunit-completions.git %APPDATA%\Sublime/ Text/ 2/Packages/phpunit-completions`
3. Restart Sublime Text to complete installation. The features listed above should now be available.

## Contributing

Your issue reports and pull requests are always welcome.

## Changelog

See [CHANGELOG.md](CHANGELOG.md).

## License

Released under the [BSD 3-Clause License](LICENSE).

[Package Control]: https://packagecontrol.io/browse/authors/gerardroche
[PHP Grammar]: https://packagecontrol.io/browse/authors/gerardroche
[PHP Completions]: https://packagecontrol.io/browse/authors/gerardroche
[PHP Snippets]: https://packagecontrol.io/browse/authors/gerardroche
[PHPUnit]: https://packagecontrol.io/browse/authors/gerardroche
[PHPUnit Completions]: https://packagecontrol.io/browse/authors/gerardroche
[PHPUnit Snippets]: https://packagecontrol.io/browse/authors/gerardroche
[Composer]: https://getcomposer.org
