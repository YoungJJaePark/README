Untitled
================

mpg 데이터 분석
===============

mpg 데이터 분석
---------------

### mpg 데이터 분석

#### mpg 데이터 분석

`mpg` 데이터로 그래프를 생성한다. `x`축에는 cty 변수를 넣었다. `y`축에는 hwy 변수를 넣었다.

``` r
library(ggplot2)
```

    ## Warning: package 'ggplot2' was built under R version 3.4.2

``` r
ggplot(data=mpg, aes(x=cty, y=hwy))+geom_point()
```

![](rmd1_files/figure-markdown_github/unnamed-chunk-1-1.png)

cty가 증가할 수록 hwy가 증가하는 것으로 나타났다.
