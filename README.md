# vegetarian

Jost diversity measures for community data: alpha, beta and gamma diversities and similarity indices, with bootstrap confidence intervals.

Compatibility updates by Renova.

Version 1.2.9001: the internal `do.call()` calls use the full argument name `args` instead of the partial `arg`, a top-level `require(stats)` is removed, `M.homog()` converts a data-frame `abundances2` to a matrix when its column names match `abundances`, and the help pages drop empty `\note`/`\details` sections and wrap long usage lines. The DESCRIPTION gains `Authors@R` and drops the stale `Date`.

## Install

```r
install.packages("vegetarian", repos = c(
  Renova = "https://renova-r.r-universe.dev",
  CRAN = "https://cloud.r-project.org"
))
```

See the [R-universe package page](https://renova-r.r-universe.dev/vegetarian) for builds and installation. This release is tagged on GitHub as `renova-1.2.9001`:

```r
remotes::install_github("renova-r/vegetarian@renova-1.2.9001")
```

[Release notes](NEWS.md) · [Renova package directory](https://github.com/renova-r/revival-catalog)

vegetarian is by Noah Charney (maintainer) and Sydne Record; the original CRAN package is at <https://CRAN.R-project.org/package=vegetarian>. License: GPL-2; see [COPYING](COPYING).
