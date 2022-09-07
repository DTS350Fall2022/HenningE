---
title: "HappyLittleMarkdown"
author: "Ellesa Henning"
date: "9/7/2022"
output: 
  html_document:
    theme: spacelab
    keep_md: true
---



Ever wonder what the sine of pi/4ths is?


```
## [1] 0.7071068
```

###KAPOW!
...
Anyway.



Variable names must start with a letter, but after that first letter can contain letters, numbers, underscores, and periods. Opt for descriptive names, preferably all lowercase words separated by underscores.

Allowed:
snake_man
SNAKEY.BOI
SnAkE5_1n_h4t5

Not Allowed:
5nake_man (cannot start with numbers)
snake&boy (cannot contain symbols other than '_' and '.')
_.epic yo (must start with letter, cannot contain spaces or bad things will happen)


```
## [1]  1.000000  9.166667 17.333333 25.500000 33.666667 41.833333 50.000000
```

```
## [1] TRUE
```

The sign '==' is basically a question mark. Is the left value equal to the right? If yes, it outputs a 'TRUE' and if not, a 'FALSE'.


```
## [1] TRUE
```

This statement is true, because the '|' means 'OR'. While 7+4==12 outputs a 'FALSE', 5-4==1 outputs a 'TRUE, which is all that's required for a final 'TRUE' result.

### Chapter 4
##### Problems 1-3

###### 1.
I'm not entirely sure what the second 'i' is (or more accurately, not 'i'), but it's not the same character as is in the top variable, and is therefore not the same variable. 

###### 2.


The error givent is that the object 'displ' is not found. This is because a typo was made earlier, with the variable being 'dota' instead of 'data'. Later, the error will be about another typo later, in which the variable is 'fliter' instead of 'filter', along with an equal sign instead of a double equal sign, and the dataset is called 'diamonds' not 'diamond'.


```
## -- Attaching packages --------------------------------------- tidyverse 1.3.2 --
## v ggplot2 3.3.6     v purrr   0.3.4
## v tibble  3.1.8     v dplyr   1.0.9
## v tidyr   1.2.0     v stringr 1.4.1
## v readr   2.1.2     v forcats 0.5.2
## -- Conflicts ------------------------------------------ tidyverse_conflicts() --
## x dplyr::filter() masks stats::filter()
## x dplyr::lag()    masks stats::lag()
```

![](Task2_files/figure-html/unnamed-chunk-6-1.png)<!-- -->

```
## # A tibble: 70 x 11
##    manufacturer model      displ  year   cyl trans drv     cty   hwy fl    class
##    <chr>        <chr>      <dbl> <int> <int> <chr> <chr> <int> <int> <chr> <chr>
##  1 audi         a6 quattro   4.2  2008     8 auto~ 4        16    23 p     mids~
##  2 chevrolet    c1500 sub~   5.3  2008     8 auto~ r        14    20 r     suv  
##  3 chevrolet    c1500 sub~   5.3  2008     8 auto~ r        11    15 e     suv  
##  4 chevrolet    c1500 sub~   5.3  2008     8 auto~ r        14    20 r     suv  
##  5 chevrolet    c1500 sub~   5.7  1999     8 auto~ r        13    17 r     suv  
##  6 chevrolet    c1500 sub~   6    2008     8 auto~ r        12    17 r     suv  
##  7 chevrolet    corvette     5.7  1999     8 manu~ r        16    26 p     2sea~
##  8 chevrolet    corvette     5.7  1999     8 auto~ r        15    23 p     2sea~
##  9 chevrolet    corvette     6.2  2008     8 manu~ r        16    26 p     2sea~
## 10 chevrolet    corvette     6.2  2008     8 auto~ r        15    25 p     2sea~
## # ... with 60 more rows
```

```
## # A tibble: 32 x 10
##    carat cut     color clarity depth table price     x     y     z
##    <dbl> <ord>   <ord> <ord>   <dbl> <dbl> <int> <dbl> <dbl> <dbl>
##  1  3.01 Premium I     I1       62.7    58  8040  9.1   8.97  5.67
##  2  3.11 Fair    J     I1       65.9    57  9823  9.15  9.02  5.98
##  3  3.01 Premium F     I1       62.2    56  9925  9.24  9.13  5.73
##  4  3.05 Premium E     I1       60.9    58 10453  9.26  9.25  5.66
##  5  3.02 Fair    I     I1       65.2    56 10577  9.11  9.02  5.91
##  6  3.01 Fair    H     I1       56.1    62 10761  9.54  9.38  5.31
##  7  3.65 Fair    H     I1       67.1    53 11668  9.53  9.48  6.38
##  8  3.24 Premium H     I1       62.1    58 12300  9.44  9.4   5.85
##  9  3.22 Ideal   I     I1       62.6    55 12545  9.49  9.42  5.92
## 10  3.5  Ideal   H     I1       62.8    57 12587  9.65  9.59  6.03
## # ... with 22 more rows
```

###### 3.
The combination Alt + Shift + K produces a list of keyboard shortcuts. These can also be accessed from the Help Menu. 
