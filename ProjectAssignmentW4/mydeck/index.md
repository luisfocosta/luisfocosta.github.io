---
title       : "Analysis of US Weather Events and impact on Public Health and Property Damage"
subtitle    : 
author      : "Luis Costa"
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---



## Synopsis

This report is based on the U.S. National Oceanic and Atmospheric Administration (NOAA) database to assess human and property costs associated with specific weather event types.

In this report I hope to address these questions:

1. Across the United States, which types of events (as indicated in the 𝙴𝚅𝚃𝚈𝙿𝙴 variable) are most harmful with respect to population health?
2. Across the United States, which types of events have the greatest economic consequences?

This data analysis is exploratory and the results can be further fine tuned by curating the dataset.

(This is a report based on my work for Reproducible Research course. Full report can be found here: http://rpubs.com/luisfocosta/256259)



---

(Data analysis withheld)

The event types (7) records) which will be assessed are:


```
##         event_types
## 1           TORNADO
## 2              HAIL
## 3         AVALANCHE
## 4             FLOOD
## 5         HURRICANE
## 6           DROUGHT
## 7 HURRICANE/TYPHOON
```

---

## Results

Which types of events are most harmful with respect to population health?

![plot of chunk unnamed-chunk-3](assets/fig/unnamed-chunk-3-1.png)

---

Which types of events have the greatest economic consequences?

![plot of chunk unnamed-chunk-4](assets/fig/unnamed-chunk-4-1.png)





