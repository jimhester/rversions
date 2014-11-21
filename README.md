


# rversions — query which versions R-release and R-oldrel refer to

## Installation


```r
devtools::install_github("metacran/rversions")
```

```
#> Downloading github repo metacran/rversions@master
#> Installing rversions
#> '/Library/Frameworks/R.framework/Resources/bin/R' --vanilla CMD INSTALL  \
#>   '/private/var/folders/ws/7rmdm_cn2pd8l1c3lqyycv0c0000gn/T/Rtmp7Bn0Gw/devtools1d5a4574b2cc/metacran-rversions-8f23cbe'  \
#>   --library='/Library/Frameworks/R.framework/Versions/3.1/Resources/library'  \
#>   --install-tests
```

## Usage


```r
library(rversions)
r_versions()
```

```
#> release  oldrel 
#> "3.1.2" "3.0.3"
```

## License

MIT