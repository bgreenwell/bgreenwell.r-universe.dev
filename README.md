# bgreenwell.r-universe.dev

Registry for my [R-universe](https://bgreenwell.r-universe.dev) packages.

## Packages

| Package | Description |
|---------|-------------|
| [fastshap](https://bgreenwell.r-universe.dev/fastshap) | Fast approximate Shapley values for any supervised learning model |
| [vip](https://bgreenwell.r-universe.dev/vip) | Variable importance plots for machine learning models |
| [pdp](https://bgreenwell.r-universe.dev/pdp) | Partial dependence plots |
| [investr](https://bgreenwell.r-universe.dev/investr) | Inverse estimation in R |
| [sure](https://bgreenwell.r-universe.dev/sure) | Surrogate residuals for ordinal and general regression models |

## Installation

**From R-universe** (latest development versions, binaries available):

```r
install.packages("fastshap", repos = c("https://bgreenwell.r-universe.dev", "https://cloud.r-project.org"))
```

Or with [pak](https://pak.r-lib.org/):

```r
pak::repo_add("https://bgreenwell.r-universe.dev")
pak::pak("fastshap")
```

**From GitHub** (development versions via pak):

```r
pak::pak("bgreenwell/fastshap")
```

**From CRAN** (stable releases):

```r
install.packages("fastshap")
```
