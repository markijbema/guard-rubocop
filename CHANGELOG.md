# Changelog

## Development

## v1.0.1

* Fix inappripriate multiple run on a save with Vim ([#6](https://github.com/yujinakayama/guard-rubocop/pull/6))

## v1.0.0

* Support Guard 2.0

## v0.2.2

* Fix a bug where `progress` formatter was used when `-f` and its argument were specified without separator in `:cli` option in `Guardfile` (e.g. `-fs`)

## v0.2.1

* Fix exception when any file is deleted

## v0.2.0

* Add `:cli` option which allows to specify additional command line arguments
* Support JRuby and Rubinius in 1.9 modes

## v0.1.0

* Update RuboCop dependency to 0.9 or later and earlier than 1.0
* Rework with JSON formatter
* Change the displayed text to "Inspecting ..."
* Print relative file paths when they are under current working directory

## v0.0.4

* Specify dependency on rubocop gem as under 0.9.0
* Force RuboCop to colorize output even though output is not TTY
* Revert "Use rubocop 0.6.1 --no-color option instead of uncoloring colored output"

## v0.0.3

* Use rubocop 0.6.1 --no-color option instead of uncoloring colored output

## v0.0.2

* Fix capitalization of the name RuboCop in notification title

## v0.0.1

* Initial release
