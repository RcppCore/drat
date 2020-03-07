## drat repository

This [drat](http://dirk.eddelbuettel.com/code/drat.html) package repository provides packages from other RcppCore code repositories.

### Usage

#### Usage via drat

```{.r}
# first add the repo
drat:::add("RcppCore")
# either install just one or more given packages
install.packages("Rcpp")     
# or update already installed packages
update.packages()
```

#### Usage without drat

```{r}
# pass the repo info directly to install.packages()
install.packages("Rcpp", repos="https://RcppCore.github.io/drat")
```

#### Usage without drat on the shell

```{sh}
Rscript -e 'install.packages("Rcpp", repos="https://RcppCore.github.io/drat")'
```


### License

Packages in this repository are available under their respective license, which is generally GPL version 2 or newer.
