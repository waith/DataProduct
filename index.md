---
title       : Develop Data Product Project
subtitle    : Conversion Feet and Inches to CM
author      : 
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Slide 2

Background
----------

This is the Develop Data Product Course Project.

The Name of App is Conversion Feet and Inches to CM.

--- .class #id 

## Slide 3

Data entry
----------
The User will key in Feet and Inches on the left.

Result display
-------------
The App will repeat the details on the right for verificatication.

The result will be shown after that.

--- .class #id 


## Slide 4

Calculation Methodology
-----------------------

The calculation is to turn the inputs into inches (1 foot = 12 inches) first.  

Total number of inches will be equal to feet x 12 + inches.

Total number of inches will then times 2.54 (1 inch = 2.54 cm) to arrive at cm.


--- .class #id 

## Slide 5

An Example
----------

The following r scripts show an example of converting 5 feet 7 inches to cm.


```r
feet<-5
inches<-7
cm<-(feet*12+inches)*2.54
cm
```

```
## [1] 170.2
```


Conclusion
----------

It is very easy to use. 

Try it out!

https://waith.shinyapps.io/devdataproduct/

