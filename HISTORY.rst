.. :changelog:

History
-------

0.4.2 (2014-05-22)
+++++++++++++++++++

* Convert python-requests bytes to string when using Python 3

0.4.1 (2014-05-22)
+++++++++++++++++++

* Replaced `json262` with `standardjson` package.

0.4.0 (2014-05-20)
++++++++++++++++++

* Replaced `utils.encoders` with `json262` package.
* utf-8 encoding everywhere
* Add `from `__future__ import absolute_import` everywhere.

0.3.2 (2014-05-17)
++++++++++++++++++

* Brought in simplified `cached_property` decorator


0.3.1 (2014-05-15)
++++++++++++++++++

* Added more Senderable attributes to make it easier to track what's going on.
* Added the missing webhooks.sender package to setup.py.


0.3.0 (2014-05-14)
++++++++++++++++++

* Added extensible Senderable class to expedite creating new senders.
* Added async_redis sender.
* Added travis-ci.

0.2.0 (2014-05-13)
++++++++++++++++++

* Added functioning hook decorator.
* Ramped up test coverage.
* Hash functions placed in their own module.
* Cleaned up JSON encoder thanks to Audrey Roy Greenfeld!

0.1.0 (2014-05-07)
++++++++++++++++++

* First release on PyPI.