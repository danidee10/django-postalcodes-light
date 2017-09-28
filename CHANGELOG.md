# Changelog

All notable changes to this project will be documented in this file.

## 0.2.1 (2017-09-28)

* Support for Python 2.7 and Django 1.8 was added
* The `requests` library is now properly marked as a dependency in `setup.py`

## 0.2.0 (2017-09-11)

* Added `unique_together` constraint for `('country_code', 'postal_code')`
* Duplicate postal codes will now by skipped by `import_postalcodes`

## 0.1.1 (2017-08-29)

* Added `import_postalcodes` management command

## 0.1.0 (2017-08-29)

* Initial release
