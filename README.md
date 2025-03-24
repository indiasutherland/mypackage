
<!-- README.md is generated from README.Rmd. Please edit that file -->

# mypackage

<!-- badges: start -->

[![R-CMD-check](https://github.com/indiasutherland/mypackage/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/indiasutherland/mypackage/actions/workflows/R-CMD-check.yaml)
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
#>   \
#>    \
#> 
#>      /\-/\
#>     /a a  \                                 _
#>    =\ Y  =/-~~~~~~-,_______________________/ )
#>      ‛^--‛          ________________________/
#>        \           /
#>        ||  |---‛\  \
#>   jgs  (_(__|   ((__|
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
#>                   \
#>                    \
#> 
#>            .-._   _ _ _ _ _ _ _ _
#> .-''-.__.-'00  '-' ' ' ' ' ' ' ' '-.
#> '.___ '    .   .--_'-' '-' '-' _'-' '._
#> V: V 'vv-'   '_   '.       .'  _..' '.'.
#>   '=.____.=_.--'   :_.__.__:_   '.   : :
#>            (((____.-'        '-.  /   : :
#> snd                          (((-'\ .' /
#>                            _____..'  .'
#>                           '-._____.-'
```
