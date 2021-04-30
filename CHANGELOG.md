# Changelog

Versioning complies with [semantic versioning (semver)](http://semver.org/).

<!-- NOTE: An entry template for a new version is automatically added each time `make version` is called. Fill in changes afterwards. -->

* **[v0.1.6](https://github.com/mklement0/perli/compare/v0.1.5...v0.1.6)** (2021-04-30):
  * [enhancement] Package is now installable on Android too, where @matheusfillipe assures me that `perli` works too (tip of the hat for the PR).

* **[v0.1.5](https://github.com/mklement0/perli/compare/v0.1.4...v0.1.5)** (2021-02-23):
  * [fix] Compatibility with `rlwrap` version 0.45, which in combination with Perl's `exec` function caused a breaking change.

* **[v0.1.4](https://github.com/mklement0/perli/compare/v0.1.3...v0.1.4)** (2019-02-11):
  * [fix] Ammends v0.1.3 to auto-flush stderr too.

* **[v0.1.3](https://github.com/mklement0/perli/compare/v0.1.2...v0.1.3)** (2019-02-11):
  * [enhancement] Auto-flushing of stdout activated to support invocation from editors such as [neovim](https://github.com/neovim/neovim) - fixes #4

* **[v0.1.2](https://github.com/mklement0/perli/compare/v0.1.1...v0.1.2)** (2015-09-30):
  * [fix] Fixed inability to define global variables (without `my`) in older Perl versions (e.g., v5.14).

* **[v0.1.1](https://github.com/mklement0/perli/compare/v0.1.0...v0.1.1)** (2015-09-24):
  * Project-status corrected in read-me.

* **v0.1.0** (2015-09-24):
  * Initial release.
