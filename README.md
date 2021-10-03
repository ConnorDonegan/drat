
## repository for my R packages

This repository holds R packages for downloading from R. 

## basic usage

To install an R package found in this repository, use:
```
if (!require(drat)) install.packages("drat")
drat::addRepo("connordonegan")
install.packages("geostan")
```

