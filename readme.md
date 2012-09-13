# A minimal R package

Everything about an R package when you want to learn how to develop an R package. Specifically, it has examples for

- DESCRIPTION
- roxygen documentation
- namespace
- S3 generic functions
- C code
- datasets
- demos
- Sweave vignettes

Forget about `package.skeleton()`; you will regret learning that "official" function one day. The Rd documentation, NAMESPACE and the `Collate` field in DESCRIPTION are automatically generated by **roxygen2**. This is how I generated them:

```r
library(roxygen2)
library(Rd2roxygen)
rab('rmini')
```
