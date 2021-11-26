# intro-git

A [`xaringan`](https://cran.r-project.org/web/packages/xaringan/index.html) presentation to introduce [`git`](https://git-scm.com/) and [`GitHub`](https://github.com).



## Setup

```{r eval = FALSE}
install.packages("rmarkdown")
install.packages("xaringan")
```


## Contributing

To modify the presentation, edit the `index.Rmd` and then:

```{r eval = FALSE}
rmarkdown::render(input         = "index.Rmd",
                  output_format = "xaringan::moon_reader",
                  output_file   = "index.html", clean = TRUE)
```
