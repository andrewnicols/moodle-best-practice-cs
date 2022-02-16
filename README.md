Moodle Coding Style with added Best Practice
============================================

This is an extended version of the (Moodle Coding style)[https://docs.moodle.org/dev/Coding_style] with added opionated best practices.

## Installation
1. Install phpcs
```
composer global require squizlabs/php_codesniffer
```
2. Add the local copy of moodle-local_codechecker with required fixes
```
composer global config repositories.moodle-local_codechecker vcs https://github.com/andrewnicols/moodle-local_codechecker
composer global require moodlehq/moodle-local_codechecker="dev-composer"
```
3. Install this package
composer global require andrewnicols/moodlebestpractice
