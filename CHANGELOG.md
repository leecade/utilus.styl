---
# Utilus.styl Changelog
---

## v0.12.0 (2014-04-06)

- Added `called_from` function.
- Added `current_media` function.
- Added proper handling of media queries with `cache`.
- Added the function's name to the `cache`'s keys.
- Fixed the `flush_media` from flushing the already flushed cache on the second call.
- Updated Stylus dep to `0.43`.

## v0.11.0 (2014-03-30)

- Added `one_em` function, for getting the contextual relative unit.

## v0.10.2 (2014-03-16)

- Fixed `cache` to use proper placeholders.

## v0.10.1 (2014-02-09)

- Fixed `utilus_collect_by_type` to work with hashes, #20.

## v0.10.0 (2014-01-23)

- Added `margin-`/`padding-`-`x`/`y` helpers.
- Added `negate` function to negate numbers in lists.
- Added `extrude` and `extrude-…` helpers.

## v0.9.0 (2014-01-20)

- Added the one and powerful `media` helper.
- Added `cache` function.
- Stylus dep up.
- Imports to requires.
- Fixed is_array to work with hashes.

## v0.8.0 (2013-12-14)

- Reorganized files, added better test-runner.
- Refactored rgb2rgba, fixed a few bugs in it.

## v0.7.0

- Using new Stylus with hashes.
- Better getters (use hash if possible).
- Added `collect_by_type` function.
- Fixed non-found sides.

## v0.6.1

- Fixed `is_function` to be native js plug-in for better performance.

## v0.6.0

- Added `is_function` func, for checking existance of interpolated functions.
- Added chain hash getter (could be used for parents etc.).
- `any` update to getter.

## v0.5.0 — v0.5.1

- Fixed getters with function idents.
- Removed obsoltete funcs.

## v0.4.0 — v0.4.2

- Fixed `get` and `is_hash`.
- Playing with semver.

## v0.1.0 — v0.3.0

- Namespaced all the things with aliases.
- Added Travis

## Pre v0.1.0

_A lot of initial stuff_
