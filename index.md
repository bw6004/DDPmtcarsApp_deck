---

title       : mtcars Data Analysis - Shiny App
subtitle    : Developing Data Products Project - Pitch Slidify 
author      : Jayaprakash
job         : Fri, 17 Apr 2015 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides

---

## Introduction

This shiny application presents exploratory data analysis of mtcars dataset. Choose the number of cylinders between (4, 6 and 8) and the transmission type (Automatic or Manual) to get the summary statistics and the corresponding bar chart is rendered in the plot tab.


[Application Github Repository](https://github.com/somalinga-jayaprakash/DevelopingDataProducts) 

--- .class1 #id1 

## Input User Interface

On the left Sidebar, a radio button input for number of cylinders and drop down for transmission type is displayed as depicted below.

![input](SidebarPanel.PNG) 


--- .class2 #id2 

## Output Tab1 - Stats Summary

Depending on the number of cylinders (4, 6 and 8) and the transmission type  (Automatic or Manual) chosen, corresponding summary statistics, standard deviation and data view are shown in the Main Panel.


```
##    Min. 1st Qu.  Median    Mean 3rd Qu.    Max. 
##   21.50   22.15   22.80   22.90   23.60   24.40
```

```
## [1] 1.452584
```

```
##                mpg cyl  disp hp drat    wt  qsec vs am gear carb
## Merc 240D     24.4   4 146.7 62 3.69 3.190 20.00  1  0    4    2
## Merc 230      22.8   4 140.8 95 3.92 3.150 22.90  1  0    4    2
## Toyota Corona 21.5   4 120.1 97 3.70 2.465 20.01  1  0    3    1
```


--- .class3 #id3 

## Output Tab2 - Plot 

When you click on the Plot Tab on the right Main Panel, depending on the number of cylinders (4, 6 and 8) and the transmission type  (Automatic or Manual) chosen, corresponding bar plot for Model by Miles Per Gallon is rendered in the Main Panel.

![input](Plot.PNG) 
