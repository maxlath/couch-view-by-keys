# CHANGELOG
*versions follow [SemVer](http://semver.org)*

## 4.0.0 - 2020-05-11
* BREAKING CHANGE: repurposed the `-d` option to be short for `--docs` (instead of `--debug`)
* Add `-d, --docs` and `-v, --values` option
* Set `'reduce=false` by default

## 3.0.0 - 2020-01-17
* BREAKING CHANGE: made the output consistent: all request return row data, instead of having some request return docs only

## 2.0.0 - 2020-01-17
* BREAKING CHANGE: the default format is now newline-delimited JSON, each line is a valid JSON object
* Added support for using `_all_docs` instead of a views
