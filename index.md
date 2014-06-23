---
title       : Simple Slider App Show
subtitle    : app shows sliders of shiny with R
author      : Lu Lu
job         : student
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Purpose of the Application

This shiny app -- simple slider gives a demontration of few possible slider options could be implemented with shiny:
1. slider with a single poit
2. slider with a range
3. custom format slider with animation

Here's link for the simple slider app:
https://lulu.shinyapps.io/lulu/


---

## Example

Here's a code for the clider with animation with custom intercal to control speed and adding looping function



```r
sliderInput("animation", "Looping Animation:", 1, 2000, 1, step = 10, 
                animate=animationOptions(interval=300, loop=TRUE))
  ),
```


---

## Futher Study

You could find more interesting 'shiny' application with R here:

http://rstudio.github.io/shiny/tutorial/
