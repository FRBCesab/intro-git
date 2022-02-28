# intro-git

[![pages-build-deployment](https://github.com/FRBCesab/intro-git/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/FRBCesab/intro-git/actions/workflows/pages/pages-build-deployment)

A [`xaringan`](https://cran.r-project.org/web/packages/xaringan/index.html) presentation to introduce [`git`](https://git-scm.com/) and [`GitHub`](https://github.com).



## Setup

You'll need these two R packages: `rmarkdown` and `xaringan`.

```{r}
install.packages(c("rmarkdown", "xaringan"))
```


## Contributing

To modify the slides, edit the `index.Rmd` and then:

```{r}
rmarkdown::render("index.Rmd")
```
