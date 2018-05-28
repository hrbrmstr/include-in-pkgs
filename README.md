
<!-- README.md is generated from README.Rmd. Please edit that file -->

# include-in-pkgs

R code/files that are meant to be *copied into new packages* (i.e. this
repo is not a pkg just files with code) to both reduce dependencies in
general but also reduce dependencies on compiled code. The compiled code
equivalents are (generally) faster than these and most of them also have
more robust features. Basically: use these components if they cover your
use-cases *and* if the benefits of a thinner dependency stack outweigh
the performance penalty costs.

Contributions can be made via PR or issues.

## Available things

  - `is_empty()`
  - `%l0%`
  - `%||%`
  - `%@%`
  - `safely()`
  - `quietly()`
  - `possibly()`
  - `keep()`
  - `discard()`
  - `compact()`
  - `bind_rows()`
  - `map()`
  - `map_chr()`
  - `map_dbl()`
  - `map_df()`
  - `map_int()`
  - `map_lgl()`
  - `map2()`
  - `map2_chr()`
  - `map2_dbl()`
  - `map2_df()`
  - `map2_int()`
  - `map2_lgl()`

## Code of Conduct

Please note that this project is released with a [Contributor Code of
Conduct](CODE_OF_CONDUCT.md). By participating in this project you agree
to abide by its terms.
