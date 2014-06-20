---
title       : MEANER
subtitle    : A Slidify app for calculating means
author      : Mikhail Voloshin
job         : Data Scientist
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax, quiz, bootstrap]
mode        : selfcontained # {standalone, draft}
---

## The Problem

- Imagine you have a bunch of numbers

- You want to find their average (arithmetic mean).

$$
\frac{1}{n} \sum_{i=1}^{n} x_{i}
$$

---

## The Solution

**MEANER!**

- Shiny app (R)
- Enter a list of numbers
- MEANER calculates the mean

---

## Powered by R

MEANER uses R's Shiny app framework to compute means.


```r
mean(c(5,6,1,2))
```

```
## [1] 3.5
```

---

## Try it yourself!

**MEANER** is hosted on ShinyApps.io.

Try it yourself!

https://omedalus.shinyapps.io/meaner/


---
