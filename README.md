
<!-- README.md is generated from README.Rmd. Please edit that file -->
trekcolors <img src="man/figures/logo.png" style="margin-left:10px;margin-bottom:5px;" width="120" align="right">
=================================================================================================================

**Author:** [Matthew Leonawicz](https://leonawicz.github.io/blog/) <a href="https://orcid.org/0000-0001-9452-2771" target="orcid.widget"> <image class="orcid" src="https://members.orcid.org/sites/default/files/vector_iD_icon.svg" height="16"></a> <br/> **License:** [MIT](https://opensource.org/licenses/MIT)<br/>

[![CRAN status](http://www.r-pkg.org/badges/version/trekcolors)](https://cran.r-project.org/package=trekcolors) [![CRAN downloads](http://cranlogs.r-pkg.org/badges/grand-total/trekcolors)](https://cran.r-project.org/package=trekcolors) [![Rdoc](http://www.rdocumentation.org/badges/version/trekcolors)](http://www.rdocumentation.org/packages/trekcolors) [![Travis build status](https://travis-ci.org/leonawicz/trekcolors.svg?branch=master)](https://travis-ci.org/leonawicz/trekcolors) [![AppVeyor build status](https://ci.appveyor.com/api/projects/status/github/leonawicz/trekcolors?branch=master&svg=true)](https://ci.appveyor.com/project/leonawicz/trekcolors) [![Codecov test coverage](https://codecov.io/gh/leonawicz/trekcolors/branch/master/graph/badge.svg)](https://codecov.io/gh/leonawicz/trekcolors?branch=master)

The `trekcolors` package provides a collection of color palettes based on Star Trek.

Installation
------------

You can install the development version of `trekcolors` from GitHub with:

``` r
# install.packages("remotes")
remotes::install_github("leonawicz/trekcolors")
```

Example
-------

``` r
library(trekcolors)
trekpal("lcars2357")
#> [1] "#ffff99" "#ff9933" "#ffcc99" "#ffcc66" "#cc99cc" "#664466" "#99ccff"
#> [8] "#3366cc" "#006699"

# See available palette names
trekpal()
#>  [1] "andorian"            "breen"               "cardassian"         
#>  [4] "cardassian2"         "cardassian3"         "cardassian4"        
#>  [7] "cardassian5"         "cardassian6"         "cardassian7"        
#> [10] "cardassian8"         "cardassian9"         "cardassian10"       
#> [13] "ferengi"             "ferengi2"            "ferengi3"           
#> [16] "klingon"             "klingon2"            "lcarscolors"        
#> [19] "lcars2357"           "lcars2369"           "lcars2375"          
#> [22] "lcars2379"           "lcars_alt"           "lcars_first_contact"
#> [25] "lcars_nemesis"       "lcars_nx01"          "lcars_29c"          
#> [28] "lcars_23c"           "lcars_red_alert"     "romulan"            
#> [31] "romulan2"            "starfleet"           "ufp"                
#> [34] "red_alert"           "yellow_alert"        "blue_alert"         
#> [37] "no_alert"            "black_alert"
```