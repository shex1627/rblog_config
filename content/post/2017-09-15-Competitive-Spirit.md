---
layout: post
title: Getting Better at Data Analysis 1
category: learning
tags:
keywords:
---

Working on my Data Analysis project yesterday, I realize my current EDA and Data Analysis project is so 
inefficient.

First, I am spending too much time trying to make a particular graph, using a technology(ggplot2) that I am 
not familiar with. This distracts me from my analysis process. Also in terms of making graphs, I have to get
familiar ggplot2, and learn how to make informative graphs. Googling "how to make XX using ggplot2" is very
tedious and inefficient, besides the trial-and-error of making better graphs.  

Being good takes hours and hours of deliberate practice. I think there are a few important metric for
being better at this:  

1. How much I am learning from the best?  
Roger Peng's video is pretty helpful. Maybe I should check datatau more. Also Andrew Ng's course on *Structuring
Machine Learning Project* definitely worth a second visit. Reading EfficientR is super good. It taught me many helpful
technical tips, such as benchmarking. I tested library *Tidyverse*'s **mutate** function on transforming a column,
it gives me 10x(3s) performance, comparing to using a base R function **sapply**;I also tried compiling the mapping
function but didn't very little in that case.  
2. How much time I spent streching my limits? Need to force myself from making poor decisions, such as overspending my
time on making beautiful plots before finishing my analysis;also need to force myself to learn ggplot2 comprehensively,
reduce amount of time I have to google to make a plot.  
