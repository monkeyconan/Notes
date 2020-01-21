[reference]<http://tinyheero.github.io/jekyll/update/2015/07/26/making-your-first-R-package.html>


#### install necessary package
install.packages('devtools')
install.packages('roxygen2')

#### create the framework of the package
devtools::create('package_name') # change the package-name

#### write functions in R folder

#### add documentation, use #'export

#### add package in DESCRIPTION
devtools::document()

#### store Data for the package

* data => binary only (.rda)
* inst/extdata => raw data
access raw file: system.file("extdata", "model-coef.csv", package = "package_name")


#### make vignettes
usethis::use_vignette("vignette_name1")

#### install package
devtools::install("package_name")
library("package_name")

#### update package,iteration

* update code
* remove NAMESPACE
* install("package_name")













