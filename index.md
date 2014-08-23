---
title       : Dhruv K Pant Slidify Presentation
subtitle    : 
author      : Dhruv K Pant
job         : Bioinformatics Scientist
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Goal of the Analysis - 
To explore the 'IRIS' dataset and train a classifier(s) to predict the species of 
a plant when provided with certain attributes (eg. petal length ..)


---

## Explore the IRIS dataset
This is a small dataset with 150 rows and 5 columns. 
The figure explores two parameters, petal length and sepal length 
for the 3 plant species. 

![plot of chunk unnamed-chunk-1](figure/unnamed-chunk-1.png) 

---
## Shiny App Link -
The link below displays the Shiny App. Here, the user can input various parameters (petal length ,..) and a choice of 
classifiers (Random Forest, Naive Bayes) to predict which type of plant corresponds to the chosen parameters. 


http://dhruv-github.shinyapps.io/dkp_shiny_app/

---

## Conclusions -
Two classifiers (__Random Forests__ and **Naive Bayes**) have been developed and deployed over a Shiny App to enable web based prediction 
of plant species.  One finds that the two classifiers do not always agree in their predictions.   

Additional work could include adding more 
classifiers (as drop down options) and some measure of the accuracy of the classifiers.

---




