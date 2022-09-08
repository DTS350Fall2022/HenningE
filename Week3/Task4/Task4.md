---
title: "Task4"
author: "Ellesa Henning"
date: "2022-09-08"
output: 
  html_document:
    keep_md: true
---



## DPLYR Practice:


```
## ── Attaching packages ─────────────────────────────────────── tidyverse 1.3.2 ──
## ✔ ggplot2 3.3.6      ✔ purrr   0.3.4 
## ✔ tibble  3.1.8      ✔ dplyr   1.0.10
## ✔ tidyr   1.2.0      ✔ stringr 1.4.1 
## ✔ readr   2.1.2      ✔ forcats 0.5.2 
## ── Conflicts ────────────────────────────────────────── tidyverse_conflicts() ──
## ✖ dplyr::filter() masks stats::filter()
## ✖ dplyr::lag()    masks stats::lag()
```

```
## # A tibble: 10 × 5
##    Sepal.Length Sepal.Width Petal.Length Petal.Width Species
##           <dbl>       <dbl>        <dbl>       <dbl> <fct>  
##  1          4.3         3            1.1         0.1 setosa 
##  2          4.4         2.9          1.4         0.2 setosa 
##  3          4.4         3            1.3         0.2 setosa 
##  4          4.4         3.2          1.3         0.2 setosa 
##  5          4.5         2.3          1.3         0.3 setosa 
##  6          4.6         3.1          1.5         0.2 setosa 
##  7          4.6         3.4          1.4         0.3 setosa 
##  8          4.6         3.6          1           0.2 setosa 
##  9          4.6         3.2          1.4         0.2 setosa 
## 10          4.7         3.2          1.3         0.2 setosa
```

```
## # A tibble: 3 × 5
##   Species    sep.len sep.wid pet.len pet.wid
##   <fct>        <dbl>   <dbl>   <dbl>   <dbl>
## 1 setosa        5.01    3.43    1.46   0.246
## 2 versicolor    5.94    2.77    4.26   1.33 
## 3 virginica     6.59    2.97    5.55   2.03
```

```
## # A tibble: 90 × 5
##    Sepal.Length Sepal.Width Petal.Length Petal.Width Species
##           <dbl>       <dbl>        <dbl>       <dbl> <fct>  
##  1          5.1         3.5          1.4         0.2 setosa 
##  2          4.9         3            1.4         0.2 setosa 
##  3          4.7         3.2          1.3         0.2 setosa 
##  4          4.6         3.1          1.5         0.2 setosa 
##  5          5           3.6          1.4         0.2 setosa 
##  6          5.4         3.9          1.7         0.4 setosa 
##  7          4.6         3.4          1.4         0.3 setosa 
##  8          5           3.4          1.5         0.2 setosa 
##  9          4.9         3.1          1.5         0.1 setosa 
## 10          5.4         3.7          1.5         0.2 setosa 
## # … with 80 more rows
```

```
## # A tibble: 150 × 6
##    Sepal.Length Sepal.Width Petal.Length Petal.Width Species Sepal.Size
##           <dbl>       <dbl>        <dbl>       <dbl> <fct>   <chr>     
##  1          5.1         3.5          1.4         0.2 setosa  medium    
##  2          4.9         3            1.4         0.2 setosa  small     
##  3          4.7         3.2          1.3         0.2 setosa  small     
##  4          4.6         3.1          1.5         0.2 setosa  small     
##  5          5           3.6          1.4         0.2 setosa  medium    
##  6          5.4         3.9          1.7         0.4 setosa  medium    
##  7          4.6         3.4          1.4         0.3 setosa  small     
##  8          5           3.4          1.5         0.2 setosa  medium    
##  9          4.4         2.9          1.4         0.2 setosa  small     
## 10          4.9         3.1          1.5         0.1 setosa  small     
## # … with 140 more rows
```

```
## # A tibble: 150 × 5
##    Sepal.Length Sepal.Width Petal.Length Petal.Width Species
##           <dbl>       <dbl>        <dbl>       <dbl> <fct>  
##  1          4.6         3.6          1           0.2 setosa 
##  2          4.3         3            1.1         0.1 setosa 
##  3          5.8         4            1.2         0.2 setosa 
##  4          5           3.2          1.2         0.2 setosa 
##  5          4.7         3.2          1.3         0.2 setosa 
##  6          5.4         3.9          1.3         0.4 setosa 
##  7          5.5         3.5          1.3         0.2 setosa 
##  8          4.4         3            1.3         0.2 setosa 
##  9          5           3.5          1.3         0.3 setosa 
## 10          4.5         2.3          1.3         0.3 setosa 
## # … with 140 more rows
```

```
## # A tibble: 3 × 5
##   Species    Sepal.Length Sepal.Width Petal.Length Petal.Width
##   <fct>             <dbl>       <dbl>        <dbl>       <dbl>
## 1 setosa             5.01        3.43         1.46       0.246
## 2 versicolor         5.94        2.77         4.26       1.33 
## 3 virginica          6.59        2.97         5.55       2.03
```

```
## # A tibble: 3 × 5
##   Species    Sepal.Length Sepal.Width Petal.Length Petal.Width
##   <fct>             <dbl>       <dbl>        <dbl>       <dbl>
## 1 setosa            0.352       0.379        0.174       0.105
## 2 versicolor        0.516       0.314        0.470       0.198
## 3 virginica         0.636       0.322        0.552       0.275
```

## Questions:

### 1: Do cat owners have higher rates of adhd than dog owners?
Overall, pretty much everyone said they were interested in the concept. One person had a cat, another is concerned for my mental health, and all of them are apparently mildly interested in everything. Need me a cat hating Chad to differentiate my answers.

### 2: What percent of hamsters actually die from natural causes?
Now this one was fun because it's a meme that hamsters die in the most traumatic of ways (which is tragic, don't get me wrong, I'm glad I never had a hamster). One person mentioned this, one person is interested because they have a hamster, and one person was horrified at the concept that hamsters die traumatic deaths, and wants to know the results because he wants to be scared. He was responsible with his hamsters.

### 3: How has the extremist political climate impacted the stability of political parties?
I got a really good answer here: "yes because it's significant to our generation especially since social media affects political extremism since people are more likely to engage with other people who have similar views to themselves and disengage with people who don't." Wowee! Someone else said they have this problem where they like to look at data like that. General consensus of yes. Less enthusiastic than the animal ones. 

### 4: How have policies in government and companies changed as more women have come into positions of power?
Well one person said interested, also they haven't [changed]. This is aggravating because I didn't ask him to answer the question (joking). Someone else said "this interests me because I am a woman and women >>>". I assume this is positive. One person said they were interested in all the questions because they were interesting brain scratchers. He promptly left. 

Based on my experience, I think most people are mildly interested in being briefly presented with information about a topic... maybe in a way they could glance over it and quickly grasp the concept... If only there were a way to easily convey information with little explanation... like maybe... a graph????
The connection almost makes it worth it. 
I think there's a nice little gradient of care, and you have to actively dislike the topic in order to say "no I would never want to hear about that not interested." The interest level varies. Perhaps they would be interested in looking at my sick hip and cool graphic, but not interested in gathering the information themselves. Who can blame them?

### Examples:
I found a lot of articles about cats having adhd and a few about dogs having adhd or displaying symptoms thereof, and you know how pets mimic their owners. I also found an article about cats helping ADHD symptoms. 
<https://untappedbrilliance.com/pets-and-adhd/>

Here's a buzzfeed article about hamster trauma:
<https://www.buzzfeed.com/kristatorres/hamsters-traumatizing-deaths-tiktok>
And a reddit thread on it:
<https://www.reddit.com/r/AskReddit/comments/n8qj1s/how_did_your_hamster_die_because_apparently_these/>
Hamsters die from anything.And perhaps some people do not deserve to own hamsters. This is more likely. 

There's some articles on the rise of far-right extremism, some calling it terrorism and political violence. It's all too much right now so I'm not looking into it.

Here's a link about positive impacts of women in power:
<https://ourworld.unu.edu/en/everyone-benefits-from-more-women-in-power>
There's also some general facts pages about women in power that could probably be cross referenced with other information for conclusions. I can't imagine reporting on this without being biased. 

### Professional Opinion:
My mom was a quality engineer, so I kind of feel like that's related enough to count. She loves statistics (She taught me standard deviations over the summer for fun). She mentioned that election and voter data is pretty widely available (we used it in my DTS190 class), so that would probably be something easily obtainable. Unfortunately, some of the questions I would have to ask to get my answer are probably not widely available, like if people switch parties. I don't think she considered my hamster question. She did mention that she had read an article that companies with women as the employer had higher job satisfaction ratings. 
