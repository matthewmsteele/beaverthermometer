---
title       : The Virtual Beaver Thermometer 
subtitle    : For all your beaver temperature prediction needs!
author      : Matthew M Steele
job         : 
logo        : beaver.png
framework   : revealjs          # {io2012, html5slides, shower, dzslides, ...}
revealjs: {theme: night, transition: default}
theme       : simple
#revealjs    : {theme: moon, transition:cube}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## The Virtual Beaver Thermometer
![4](assets/img/beaver.png)

### *For all your beaver temperature prediction needs!*

---

## How often have you thought to yourself, *"I wonder what the internal temperature of a sleeping beaver is?"*

Who Hasn't?

---

### But in the the past the answer to that question has always involved trapsing through the woods for hours on end. 

And when you finally find one of the ***furry little rascals***, you have the unpleasant task in front of you of getting the vermit to open its mouth and say "**Ahhhhhhhhhh**!"

--- .class #id 

### Now thanks to the Power of *Science* and *R* you can find an answer without getting your shoes dirty!!



```r
time <- 1430
activity <- 0
beaverTemp <- PredictTemperature(time=time,activity=activity)
paste("The internal temperature of a",ifelse(activity==1,"active","sleeping"),
      "beaver is",beaverTemp,"degrees Celsius.")
```

```
## [1] "The internal temperature of a sleeping beaver is 36.9357586464559 degrees Celsius."
```

---
## Now Presenting 
![4](assets/img/beaver.png)
### [*The Virtual Beaver Thermometer*](http://matthewmsteele.shinyapps.io/beaverThermometer/)
