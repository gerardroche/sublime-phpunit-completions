Sublime PHPUnit Completions Kit
===============================

Provides [PHPUnit](http://phpunit.de) [~4.2](http://semver.org)) completions for
[Sublime Text](http://www.sublimetext.com).

Completions include assertions, annotations, test-case type hints, and other
methods like `getMock()`, `markTestIncomplete()`, `setExpectedException()`.

Extensions:

- DbUnit ~1.3

All completions activate *only* in valid contexts.

Other PHP packages:

* [PHP Grammar](https://github.com/gerardroche/sublime-php-grammar)
* [PHP Snippets](https://github.com/gerardroche/sublime-php-snippets)
* [PHP Completions](https://github.com/gerardroche/sublime-phpck)

Usage
-----

> Auto complete shows the completion popup as you type, so you can fill in long
> words by typing only a few characters.
>
> Pressing <kbd>ctrl</kbd>+<kbd>space</kbd> (OSX and Windows),
> <kbd>alt</kbd>+<kbd>/</kbd> (Linux) will show the completion popup if it's not
> currently showing.  If it is showing, it'll select the next item.
>
> &mdash; [Sublime Text Documentation](http://www.sublimetext.com/docs/3/auto_complete.html)

`assertTrue|` <kbd>tab</kbd>

                      vvvvvvvvv
    $this->assertTrue(condition, message = '')

`$this->assertTrue|` <kbd>tab</kbd>

                      vvvvvvvvv
    $this->assertTrue(condition, message = '')

`class name extends phpunit|` <kbd>alt</kbd>+<kbd>/</kbd> activates type hints

    PHPUnit_Framework_TestCase
    PHPUnit_Extensions_Database_TestCase

For more details on usage see the [PHP Completions Kit](https://github.com/gerardroche/sublime-phpck).

Installation
------------

### [Git](http://git-scm.com)

Clone directly into the Sublime Text `Packages` directory.  *Locate the
`Packages` directory by using the menu item
`Preferences -> Browse Packages...`.*

### [Manual](http://www.sublimetext.com/docs/3/packages.html)

1. [Download a release](https://github.com/gerardroche/sublime-phpunitck/releases)
2. Unzip and copy it to the Sublime Text `Packages` directory.  *Locate the
`Packages` directory by using the menu item
`Preferences -> Browse Packages...`.*
