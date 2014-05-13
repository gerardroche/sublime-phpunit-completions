Sublime PHPUnit Completions Kit
===============================

Provides [PHPUnit](http://phpunit.de) completions for [Sublime Text](http://www.sublimetext.com).

> Auto complete shows the completion popup as you type, so you can fill in long
> words by typing only a few characters. &mdash; [Sublime Text auto-complete doc.](http://www.sublimetext.com/docs/3/auto_complete.html)

Usage
-----

`assertEquals`<kbd>TAB</kbd>

                      vvvvvvvvv
    $this->assertTrue(condition, message = '')

`$this->assertEquals`<kbd>TAB</kbd>

                      vvvvvvvvv
    $this->assertTrue(condition, message = '')

`class ClassTest extends phpunit`<kbd>ALT</kbd>+<kbd>/</kbd>

Provides types hints:

    PHPUnit_Framework_TestCase
    PHPUnit_Extensions_Database_TestCase

See [Sublime PHP Completions Kit](https://github.com/gerardroche/sublime-phpck#usage--features) for more usage details.

Installation
------------

### Using [Package Control](https://sublime.wbond.net/installation)

1. Open Package Control: `Preferences -> Package Control`
2. Select `Package Control: Install Package`
3. Type `PHP Completions Kit` into the search box and select the package to
install it

### Using [Git](http://git-scm.com)

Clone directly into your Sublime Text `Packages` directory.

*Locate your `Packages` directory by using the menu item
`Preferences -> Browse Packages...`.*

### [Manual](http://www.sublimetext.com/docs/3/packages.html)

1. [Download a release from GitHub](https://github.com/gerardroche/sublime-phpck/releases)
2. Unzip it and copy it to your Sublime Text `Packages` directory

*Locate your `Packages` directory by using the menu item
`Preferences -> Browse Packages...`.*
