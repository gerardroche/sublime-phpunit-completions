CHANGELOG
=========

0.4.0
-----

* Fixed: 8b1369f Completions shouldn't trigger in a class constant context e.g. self::|
* Fixed: 9e641cf Completions shouldn't trigger in a declaration context e.g. class a|

0.3.0
-----

* Updated: b429b9a PHPUnit 4.4.0

  * Added `assertArraySubset` method

0.2.2
-----

* Fixed: 5282d19 Annotations can now be triggered without having to type the @ symbol

0.2.1
-----

* Fixed: 9552886 Functions are no longer triggered in a comment context

0.2.0
-----

* Updated: e2b7390 PHPUnit 4.3.5

  * Added `expectedExceptionMessageRegExp` annotation
  * Added `isInIsolation` method

0.1.1
-----

* Fixed: Functions no longer trigger in a string context https://github.com/gerardroche/sublime-phpck/pull/6

0.1.0
-----

* Added DBUnit assertions, matchers, and other helper methods
* Added DBUnit testcase type hints
* Added Annotations
* Added Assertions, matchers, and other helper methods
* Added Test-case type hints

