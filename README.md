
<!-- README.md is generated from README.Rmd. Please edit that file -->

# mypackage

<!-- badges: start -->
<!-- badges: end -->

The goal of mypackage is to print a personalised message from me!

## Installation

You can install the development version of mypackage like so:

``` r
# install.packages("remotes") 
remotes::install_github("indiasutherland/mypackage")
```

## Example

This is a basic example which shows you how to print a generic greeting:

``` r
library(mypackage)
## basic example code
hello()
#> 
#>  ------------------------- 
#> < Hello world from India! >
#>  ------------------------- 
#>               \
#>                \
#> 
#>         /\_/\         _
#>        /``   \       / )
#>        |n n   |__   ( (
#>       =(Y =.‛`   `\  \ \
#>       {`"`        \  ) )
#>       {       /    |/ /
#>        \\   ,(     / /
#>         ) ) /-‛\  ,_.‛
#>   jgs  (,(,/ ((,,/
#> 
```

This is a basic example which shows how to print a personalised
greeting:

``` r
hello(name = "Lucy Elen")
#> 
#>  ----------------------------- 
#> < Hello Lucy Elen from India! >
#>  ----------------------------- 
#>       \
#>        \
#> 
#>         ^__^ 
#>         ($$)\ ________ 
#>         (__)\         )\ /\ 
#>              ||------w|
#>              ||      ||
```
