testRMarkdownForGithub
================
Julia Burmistrova
February 9, 2018

Insert an empty R chunk, via the “Chunk” menu in upper right of source
editor or with corresponding keyboard shortcut.

\#\#\#Question 2

``` r
x<-c(1,2,4)
q <- c(x,x,8)
mean(x)
```

    ## [1] 2.333333

``` r
sd(x) 
```

    ## [1] 1.527525

``` r
print(sd(x))
```

    ## [1] 1.527525

``` r
y <- mean(x)
s <- sd(x) 
```

Ans: Object s has been defined as standard deviation of x and we check
that by printing sd(x) and comparing that to the value to s.

\#\#\#Question
3

``` r
paste("Remote","Sensing","is","covered","in","awesomesauce!") #Make R write some words
```

    ## [1] "Remote Sensing is covered in awesomesauce!"

``` r
paste("Julia Burmistrova")
```

    ## [1] "Julia Burmistrova"

Ans: I made R print my name.
