# MetaboCoreutils 1.3

## MetaboCoreUtils 1.3.8

- Support for heavy isotopes in `countElements`/`pasteElements`/`calculateMass`
  (issue [#53](https://github.com/rformassspectrometry/MetaboCoreUtils/issues/53)).

## MetaboCoreUtils 1.3.7

- Fix bug in `containsElements` function (issue
  [#51](https://github.com/rformassspectrometry/MetaboCoreUtils/issues/51)).

## MetaboCoreUtils 1.3.6

- Add functions for Kendrick mass defects.

## MetaboCoreUtils 1.3.5

- Add missing unit tests.

## MetaboCoreUtils 1.3.4

- Add `calculateMass` function.

## MetaboCoreUtils 1.3.3

- Vectorized versions for chemical mass functions.

## MetaboCoreUtils 1.3.2

- Function for conversion of migration time to effective mobility in CE-MS.

## MetaboCoreUtils 1.3.1

- Add isotope detection functionality.

# MetaboCoreutils 1.1

## MetaboCoreUtils 1.1.3

- Add isotope detection functionality.

## MetaboCoreUtils 1.1.2

- Add already charged adduct/ion to the adduct definition.

## MetaboCoreUtils 1.1.1

- Add `correctRindex` function.
- Add `isotopologue` function to group isotopologues in MS spectra.

# MetaboCoreutils 0.99

## MetaboCoreUtils 0.99.1

- Add `[M+H-2(H2O)]+` adduct definition.

## MetaboCoreUtils 0.99.0

- Add package vignette and prepare for Bioconductor submission.

# MetaboCoreutils 0.0

## MetaboCoreUtils 0.0.3

- Add `internalStandards` and `internalStandardsNames` functions.

## MetaboCoreUtils 0.0.3

- Refactor `mass2mz` and `mz2mass` to support calculation of multiple adducts
  for multiple input values as well as user defined adduct definition.
- Add functions `adducts` to return a `data.frame` with the (built-in) adduct
  definitions.

## MetaboCoreUtils 0.0.2

- Vectorize `mass2mz` and `mz2mass` and additional performance improvement.

## MetaboCoreUtils 0.0.1

- Add utility functions to work with chemical formulas: `pasteElements`,
  `countElements` and `standardizeFormula`.
- Add utility functions to convert between m/z and monoisotopic masses based on
  provided ion adduct information.
