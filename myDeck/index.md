---
title       : The Statistical Power App
subtitle    : 
author      : 
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
---

## Overview

The Statistical Power App is a simple app made in R Shiny that returns the Statistical power for a T.Test based on the parameters that the user input.

---

## Why Statitistical Power?

When designing a test for data driven research it is important to understand what sample size you need to be able to detect a statistical pattern if one exists. Therefore you need to estimate the diffrence in e.g Mean that you expect to se if there is some real effect, and then calculate the statistical power for diffrent sample sizes with the expected Mean diffrence. This way you know how big sample size you need for you test to be usefull.

---

## Why the statistical Power App?

THe Statistical Power App makes it easy to calculate the statistical power using a intiutive GUI. The app is hosted on the cloud and accesable with any standard web browser.

---

## User's instructions


Stepwise guide how to use the app

1. Insert parameters and choose the type of t.test power calculation to be performed
2. Read date from the right part of the screen  

---

## Tecnical details

The app consists of an server.R and ui.R file. 

---



