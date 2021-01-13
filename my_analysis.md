My analysis
================

## Random number generation

“Here, we generate a random number between 0 an 10”

``` r
set.seed(1234)
number<-sample(x=0:10, size=1, replace=FALSE)
text<-paste ("My favorite number is", number)
cowsay::say(text, "cow")
```

    ## 
    ##  ----- 
    ## My favorite number is 9 
    ##  ------ 
    ##     \   ^__^ 
    ##      \  (oo)\ ________ 
    ##         (__)\         )\ /\ 
    ##              ||------w|
    ##              ||      ||
