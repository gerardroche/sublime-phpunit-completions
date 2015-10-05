# gerardroche/sublime-phpunit-completions

sublime-phpunit-completions plugin for Sublime Text. Provides decent PHPUnit completions.

## Overview

* [Features](#features)
* [Key Bindings](#key-bindings)
* [Installation](#installation)
* [Contributing](#contributing)
* [Changelog](#changelog)
* [Complementary Plugins](#complementary-plugins)
* [License](#license)

# Features

* PHPUnit [~4.4](http://semver.org)
* DbUnit [~1.3](http://semver.org)
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

1. Download or clone this repository to a directory named `phpunit-completions` in the Sublime Text Packages directory for your platform:
    * Sublime Text 3
        - Linux: `git clone https://github.com/gerardroche/sublime-phpunit-completions.git ~/.config/sublime-text-3/Packages/phpunit-completions`
        - OS X: `git clone https://github.com/gerardroche/sublime-phpunit-completions.git ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/phpunit-completions`
        - Windows: `git clone https://github.com/gerardroche/sublime-phpunit-completions.git %APPDATA%\Sublime/ Text/ 3/Packages/phpunit-completions`
    * Sublime Text 2
        - Linux: `git clone https://github.com/gerardroche/sublime-phpunit-completions.git ~/.config/sublime-text-2/Packages/phpunit-completions`
        - OS X: `git clone https://github.com/gerardroche/sublime-phpunit-completions.git ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/phpunit-completions`
        - Windows: `git clone https://github.com/gerardroche/sublime-phpunit-completions.git %APPDATA%\Sublime/ Text/ 2/Packages/phpunit-completions`
2. Restart Sublime Text to complete installation. The features listed above should now be available.

## Contributing

Issue reports and pull requests are always welcome.

## Changelog

See [CHANGELOG.md](CHANGELOG.md).

## Complementary Plugins

* [PHP Grammar](https://github.com/gerardroche/sublime-php-grammar)
* [PHP Completions](https://github.com/gerardroche/sublime-phpck)
* [PHP Snippets](https://github.com/gerardroche/sublime-php-snippets)
* [PHPUnit](https://github.com/gerardroche/sublime-phpunit)
* [PHPUnit Snippets](https://github.com/gerardroche/sublime-phpunit-snippets)

## License

Released under the [BSD 3-Clause License][LICENSE].
