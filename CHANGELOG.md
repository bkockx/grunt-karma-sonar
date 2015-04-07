<a name="0.2.2"></a>
# 0.2.2 (2015-04-02)

## Bug Fixes
- Fixed regex for finding tests with double and single quotes
- Fixed regex for finding testcases that have an autoclose tag
- Added check for files that are in the test directory but are no tests

<a name="0.2.1"></a>
# 0.2.1 (2015-04-02)

## Bug Fixes
- #17 Cannot find module 'fs-extra'

<a name="0.2.0"></a>
# 0.2.0 (2015-04-02)

## Breaking changes
- The configuration has changed.

## Features
- Added support for dry-run
- Added support for adding custom sonar properties

## Bug Fixes
- 'karma_sonar' task now stops when an error has occurred
- karma-junit-reporter reports are now processed and updated with the correct spec for classname