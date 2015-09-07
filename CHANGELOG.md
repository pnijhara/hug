Changelog
=========

### 1.3.0
- Started keeping a log of all changes between releases
- Added support for quickly exposing functions as cli clients with `hug.cli` decorator
- `hug.types.decimal` renamed to `hug.types.float_number` and `hug.types.decimal` type added that returns python Decimal
- `hug.types.accept` wrapper added, that makes it easy to customize doc strings and error handling for any preexisting type converter