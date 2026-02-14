# bias-shared-arena

Vendored version of [shared_arena](https://github.com/sebastiencs/shared-arena) with modifications for BIAS.

## Changes:

- Added `make_mut` for `ArenaArc` and `ArenaRc`.
- Added `into_raw` and `from_raw` for `ArenaArc`, `ArenaRc`, and `ArenaBox`.
- Improvements to `Arena::shrink_to_fit` for large `N`.
