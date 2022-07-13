Type coercion
================
Naomi Ekas

\##Exercise 1

-   `c(1, 1L, "C")`

my guess is R changes all three to a character I was correct!

``` r
c(1, 1L, "C")
```

    ## [1] "1" "1" "C"

\##Exercise 2 1 is a double 1L is an integer “c” is a character

``` r
1
```

    ## [1] 1

``` r
1L
```

    ## [1] 1

``` r
"C"
```

    ## [1] "C"

\#Exercise 3

all of these will come out as character

``` r
typeof(c(1, 1L, "C"))
```

    ## [1] "character"

\#Exercise 4 - `c(1L / 0, "A")` all of these will be a character

``` r
c(1L / 0, "A")
```

    ## [1] "Inf" "A"

\#Exercise 5 integer double character character

``` r
typeof(1L)
```

    ## [1] "integer"

``` r
typeof(0)
```

    ## [1] "double"

``` r
typeof(1L/0)
```

    ## [1] "double"

``` r
typeof("A")
```

    ## [1] "character"

I was wrong on the double

\#Exercise 6 all will be Characters

``` r
typeof(c(1L / 0, "A"))
```

    ## [1] "character"

\#Exercise 7 - `c(1:3, 5)`

``` r
c(1:3, 5)
```

    ## [1] 1 2 3 5

\#Exercise 8

``` r
typeof(1:3)
```

    ## [1] "integer"

``` r
typeof(5)
```

    ## [1] "double"

\#Exercise 9

``` r
typeof(c(1:3, 5))
```

    ## [1] "double"

\#Exercise 10 - `c(3, "3+")`

``` r
c(3, "3+")
```

    ## [1] "3"  "3+"

\#Exercise 11

``` r
typeof(3)
```

    ## [1] "double"

``` r
typeof("3+")
```

    ## [1] "character"

\#Exercise 12

``` r
#typeof(c(3, "3+"))
```

\#Exercise 13 - `c(NA, TRUE)`

``` r
c(NA, TRUE)
```

    ## [1]   NA TRUE

\#Exercise 14 logical

``` r
typeof(NA)
```

    ## [1] "logical"

``` r
typeof(TRUE)
```

    ## [1] "logical"

\#Exercise 15

``` r
typeof(c(NA, TRUE))
```

    ## [1] "logical"
