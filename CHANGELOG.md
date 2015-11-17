# Forked Version

First, we merged a bunch of outstanding PRs from the upstream version:

* Merged MindscapeHQ/raygun4php#58 - improves travis.yml
* Merged MindscapeHQ/raygun4php#60 - upgrades PHPUnit
* Merged MindscapeHQ/raygun4php#62 - switches to classmap autoloading instead of PSR0
* Merged MindscapeHQ/raygun4php#63 - tests default visibility

We do these first because they've been partially reviewed by MindscapeHQ
(https://github.com/MindscapeHQ/raygun4php/pull/63#issuecomment-73618449)

Then we continue with a few newer PRs, that haven't had feedback yet:

* Merged MindscapeHQ/raygun4php#69 - fixes warning/empty string on iconv conversion
* Merged MindscapeHQ/raygun4php#71 - adds support for nested exceptions
* Merged MindscapeHQ/raygun4php#77 - code standards: fixes phpdoc format
* Merged MindscapeHQ/raygun4php#79 - functional testing
* Merged MindscapeHQ/raygun4php#81 - allow setting user identifier directly

Finally, we do a couple of merge commits to fix up incompatibilities between
the above branches, and we add this changelog.

## BC

This branch should be full backward compatible, even if you're not using
composer (because no requires have been removed yet).
