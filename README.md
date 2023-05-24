# WHAT PHPUNIT COMPLETIONS IS

[![Minimum Sublime Version](https://img.shields.io/badge/sublime-%3E%3D%203.0-brightgreen.svg?style=flat-square)](https://sublimetext.com) [![Latest Version](https://img.shields.io/github/tag/gerardroche/sublime-phpunit-completions.svg?style=flat-square&label=version)](https://github.com/gerardroche/sublime-phpunit-completions/tags) [![GitHub stars](https://img.shields.io/github/stars/gerardroche/sublime-phpunit-completions.svg?style=flat-square)](https://github.com/gerardroche/sublime-phpunit-completions/stargazers)

PHPUnit completions for Sublime Text.

## FEATURES

* PHPUnit ~6
* DbUnit ~3.0
* [PSR](http://www.php-fig.org) compliant
* Scoped to minimise auto-complete noise
* Test case type hints e.g. begin typing at `class Name extends |` and any other context where a type hint is valid.
* Assertions e.g. begin typing `assert|` or `$this->assert|`
* Test case helpers e.g. begin typing `getMockBuilder|` or `$this->getMockBuilder|`
* Annotations e.g. begin typing _(any valid doc block scope)_ `/* @covers| */` or without the `@` symbol `/* covers| */`

## KEY BINDINGS

| OS X | Windows | Linux | Description |
|------|---------|-------|-------------|
| <kbd>Ctrl</kbd>+<kbd>Space</kbd> | <kbd>Ctrl</kbd>+<kbd>Space</kbd> | <kbd>Alt</kbd>+<kbd>/</kbd> | Activate completions |

To enable [tab-completions](http://docs.sublimetext.info/en/latest/extensibility/completions.html#tab-completed-completions) set `"tab_completion": true` in `Preferences → Settings - User`.

## INSTALLATION

### Manual installation

Close Sublime Text then download or clone this repository to a directory named `PHPUnitCompletions` in the Sublime Text Packages directory for your platform:

* Linux: `git clone https://github.com/gerardroche/sublime-phpunit-completions.git ~/.config/sublime-text-3/Packages/PHPUnitCompletions`
* OSX: `git clone https://github.com/gerardroche/sublime-phpunit-completions.git ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/PHPUnitCompletions`
* Windows: `git clone https://github.com/gerardroche/sublime-phpunit-completions.git %APPDATA%\Sublime/ Text/ 3/Packages/PHPUnitCompletions`

## LICENSE

Released under the [GPL-3.0-or-later License](LICENSE).
