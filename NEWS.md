# vegetarian 1.2.9001

Renova release, based on CRAN vegetarian 1.2 (archived on CRAN 2021-02-15).

- `R/vegetarian.R`: eleven `do.call(what=..., arg=...)` calls now use the full argument name `args=` (no partial argument matching).
- `R/vegetarian.R`: top-level `require(stats)` removed (stats is attached by default).
- `R/vegetarian.R`: in `M.homog()`, a data-frame `abundances2` is converted with `as.matrix()` when `abundances` is a matrix with identical column names, replacing `as.vector()` on the data frame.
- `man/*.Rd` (11 files): empty `\note{}` and `\details{}` sections removed and long `\usage` lines wrapped (documentation only).
- `DESCRIPTION`: `Authors@R` added for Noah Charney (aut, cre) and Sydne Record (aut), replacing the free-text `Author`; `Description` starts with `Computes` instead of `This package computes` (metadata only).
- `DESCRIPTION`: stale optional `Date` field removed (metadata only).

Release preparation:

- `DESCRIPTION`: `Version` set to `1.2.9001`; "Compatibility updates by Renova." appended to `Description`.
- The stale `MD5` file was removed.
- `COPYING` (GNU GPL version 2 text) was added; the `License` field is unchanged.
- `README.md` was added and is excluded from the R build.
- `NEWS.md` was added and is excluded from the R build.
