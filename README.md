Sublime PHPUnit Completions Kit
===============================

Provides [PHPUnit](http://phpunit.de) 4.2 completions for [Sublime Text](http://www.sublimetext.com)
(includes DbUnit 1.3).

> Auto complete shows the completion popup as you type, so you can fill in long
> words by typing only a few characters. &mdash; [Sublime Text Documentation](http://www.sublimetext.com/docs/3/auto_complete.html)

Completions include assertions, annotations, test-case type hints, and other
methods like `getMock()`, `markTestIncomplete()`, `setExpectedException()`.

All completions activate *only* in valid contexts.

Other completion kits:

* [PHP Completions Kit](https://github.com/gerardroche/sublime-phpck)

Usage
-----

> Pressing <kbd>ctrl</kbd>+<kbd>space</kbd> (OSX and Windows),
> <kbd>alt</kbd>+<kbd>/</kbd> (Linux) will show the completion popup if it's not
> currently showing.  If it is showing, it'll select the next item.
> &mdash; [Sublime Text Documentation](http://www.sublimetext.com/docs/3/auto_complete.html)

`assertTrue` <kbd>tab</kbd>

                      vvvvvvvvv
    $this->assertTrue(condition, message = '')

`$this->assertTrue` <kbd>tab</kbd>

                      vvvvvvvvv
    $this->assertTrue(condition, message = '')

`class name extends phpunit` <kbd>alt</kbd>+<kbd>/</kbd> activates type hints

    PHPUnit_Framework_TestCase
    PHPUnit_Extensions_Database_TestCase

For more details on usage see the [PHP Completions Kit](https://github.com/gerardroche/sublime-phpck/README.md) readme.

Installation
------------

### [Package Control](https://sublime.wbond.net/installation)

1. Open Package Control: `Preferences -> Package Control`
2. Select `Package Control: Install Package`
3. Type `PHPUnit Completions Kit` into the search box and select the package to
install it

### [Git](http://git-scm.com)

Clone directly into your Sublime Text `Packages` directory.  *Locate your
`Packages` directory by using the menu item `Preferences -> Browse Packages...`.*

### [Manual](http://www.sublimetext.com/docs/3/packages.html)

1. [Download a release](https://github.com/gerardroche/sublime-phpunitck/releases)
2. Unzip and copy it to your Sublime Text `Packages` directory.  *Locate your
`Packages` directory by using the menu item
`Preferences -> Browse Packages...`.*
