# ErlyDTL NEWS file

This file records noteworthy changes and additions to erlydtl as
suggested by the [GNU Coding
Standards](http://www.gnu.org/prep/standards/html_node/NEWS-File.html#NEWS-File).

## master (upcoming release)

* Fix compile time variables and constants (#61)

* The `vars` compile time option has been deprecated in favor of
  `default_vars`.

* Support for translation contexts (#131)

  `context` is now a reserved keyword.

* Support for plural forms in `blocktrans` blocks (#131)

  As a side effect of the this, `count` and `plural` are now reserved
  keywords (the latter only as the tag name).
