---
title: "Wedding_Menu"
author: "Nathaniel Legall"
date: "20/05/2019"
output: html_document
---

```{r echo = FALSE, results = 'asis'}
library(knitr)
knitr::opts_chunk$set(echo = TRUE)
```

## Menu

Here is our budget for the food at the wedding reception. We want their to be **genuine** vegan and vegetarian options. I'm concerned that we might miss the mark on this and end up with some of our guests eating leaf salad for five hours. 

```{r Food Table}
Menu <- read.csv(file = '~/Desktop/Wedding Planning/FingerFood.csv', header=TRUE, sep=",")
kable(Menu[,1:14], caption = "Morrisons equivelent options.")

```

*Any feedback on this would be appreciated* 

## Including Plots

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.
