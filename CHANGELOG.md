# sublime-phpunit-completions

## 0.8.0

* Added: a semicolon is now appened to all completions
* Changed: completions now only include the required parameter fields

## 0.7.0

* Renamed repository from sublime-phpck to sublime-php-completions. To change Git remote url see https://help.github.com/articles/changing-a-remote-s-url/
* Update to DbUnit 1.3.2; Adds `createArrayDataSet()` method

## 0.6.0

* Descriptions for DbUnit completions now says DbUnit
* Added some missing completions: `getMock`, `setExpectedExceptionFromAnnotation`, `setExpectedExceptionRegExp`, `atLeast`, `atMost`, `setUseErrorHandlerFromAnnotation`

## 0.5.0

* Scopes blacklists are now pretty printed
* Scopes are now sorted
* Type hints are now available in multi line comments, not just phpdocs's e.g. begin typing at `/* @var |`
* Annotations are now available in multi line comments, not just phpdoc's e.g. `/* @annotation `
* Minimise auto-complete noise: Functions and language constructs no longer activate in a "meta" scope e.g. typing at `class a extends |`

## 0.4.1

* (alister-patch-1) Spelling fix Thanks @alister #1

## 0.4.0

* Fixed: 8b1369f Completions shouldn't trigger in a class constant context e.g. self::|
* Fixed: 9e641cf Completions shouldn't trigger in a declaration context e.g. class a|

## 0.3.0

* Updated: b429b9a PHPUnit 4.4.0
* Added `assertArraySubset` method

## 0.2.2

* Fixed: 5282d19 Annotations can now be triggered without having to type the @ symbol

## 0.2.1

* Fixed: 9552886 Functions are no longer triggered in a comment context

## 0.2.0

* Updated: e2b7390 PHPUnit 4.3.5
* Added `expectedExceptionMessageRegExp` annotation
* Added `isInIsolation` method

## 0.1.1

* Fixed: Functions no longer trigger in a string context gerardroche/sublime-phpck#6

## 0.1.0

* Added DBUnit assertions, matchers, and other helper methods
* Added DBUnit testcase type hints
* Added Annotations
* Added Assertions, matchers, and other helper methods
* Added Test-case type hints

