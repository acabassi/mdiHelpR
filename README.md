# mdiHelpR
A repo for some of my MDI helper functions.

Install using:

```{r install_cmd}
devtools::install_github("stcolema/mdiHelpR")
```

On Mac OS, temporarily add 
```
SHLIB_OPENMP_CFLAGS=
SHLIB_OPENMP_CXXFLAGS=
```
to your `~/.R/Makevars` file before running the above command in R to install
without OpenMP. Otherwise follow [these instructions](https://stackoverflow.com/questions/43595457/alternate-compiler-for-installing-r-packages-clang-error-unsupported-option) for the full installation.