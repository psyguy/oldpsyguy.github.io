---
published: true
---
# Learning R: Why and How - A guide for absolute strangers

I am an electrical engineer (majoring in telecommunication) with a master degree in AI (actually, graduating in a few months), and I am currently finishing a research master in psychology this year. In my master in psychology I was mostly focused on quantitative methods, and I am working on latent trait modeling of time series. Having that said, I am quite proficient in Matlab (as I have had enough of it in my EE and AI), but I now identify as a radical R evangelist. Sadly, many of my colleagues in psychology, even those working in quantitative psychology, are total strangers to R, and I genuinely suffer from that.

I frequently hear a bunch of 'concerns' (i.e., excuses) why people are reluctant to start using R.  Here I try to address them. However, I will not talk much about computational power and efficiency of R compared to other languages (more specifically, Matlab, Python, and Julia), as I believe an average user in psychology would not notice any issues regarding the speed or efficiency. I, as a quite advanced user, have not encountered any significant efficiency problems in the past few years. In what follows, I try to encourage you to learn _the true and only way of doing statistics,_ which as everyone knows, is **R**.

**Disclaimer:** only the first figure belongs to me.

## _Why do you think I need to learn R?_ 

SPSS and Matlab are products of filthy Capitalism: they are very costly -which you would probably not care if you use university/student licenses or pirate them!- and they do not belong to the open source culture. I believe they are barriers on our way to a utopian open science.

On top of that, I believe that there is a decent consensus that SPSS sucks in general--it is limited in its functionality and the analyses it can do. It shouldn't be surprising that SPSS is getting closer and closer to its death. Fingers crossed, I hope to see it extinct with my own eyes, hopefully before 2025.

Matlab, on the other hand, is not well-suited for [quantitative] psychology; it lacks essential functions and packages and doesn't handle the kind of data we encounter in social and behavioral sciences properly. Yes, it is a functional language for [hardcore] signal analysis and control engineering (and perhaps some numerical analyses/simulations in science and engineering). However, in many cases, Python and/or Julia are better alternatives. Also, although Matlab has always been a dominant language in engineering, there are indications that it is losing it to R.

One can spot these declines in [Google Trends](https://trends.google.com/trends/explore/TIMESERIES/1554296400?hl=en-US&tz=-120&date=all&q=%2Fm%2F053_x,%2Fm%2F018fh1,%2Fm%2F0212jm&sni=3), although it is not a definite indicator of this claim. It is worth noting that Matlab owes much of its popularity to _pirates,_ mostly users from countries (such as Iran) where there are no (proper) copyright laws in order. Just take a close look at the Google Trends link, and compare Iran's rank for Matlab (1st) to 57th for R and 60th for Python.

![image](https://user-images.githubusercontent.com/8527082/55494090-6be87880-563a-11e9-8c09-830e7a8d0ce3.png)

There I was involved in a recent conversation on twitter about Matlab/R comparison [here](https://twitter.com/_psyguy/status/1113395619287175168).


## _I am already familiar with Matlab/SPSS and I’m quite ‘happy’ with it_

Are you really though? People, especially SPSS users, are usually entrapped in a kind of abusive relationship; they rely on it for their work and have to deal with its sufferings since they are too afraid to leave it and move on to a better alternative. In my opinion, some are even suffering from some sort of Stockholm syndrome. You are not alone there.

![image](https://user-images.githubusercontent.com/8527082/55495028-507e6d00-563c-11e9-9169-c02553fb4c5c.png)

## _What can R offer that others do not?_

R is fabulous. It is superior to other languages in countless ways when it comes to statistical analyses. Most importantly, it has a very active community and a ton of useful packages which satisfy most of your needs. You can perform advanced statistical modelings and analyses that required special, costly software; you can easily do advanced latent trait modelings (IRT, EFA, CFA, and SEM). I am not going to give more details here.

With R (and its siblings, Rmarkdown and Shiny) you can do things so easily that are hard to imagine elsewhere. You can make excellent LaTeX or HTML reproducible (APA) papers, technical reports, books, and blogs with [Rmarkdown](https://bookdown.org/yihui/rmarkdown/), [bookdown](https://bookdown.org/yihui/bookdown/), and [blogdown](https://bookdown.org/yihui/blogdown/). You can create interactive apps with [Shiny](https://shiny.rstudio.com/gallery/) to collect experiment data, make tutorials, and make powerful BI dashboards, and deploy them to [RStudio Shiny Server](https://www.shinyapps.io) or your own server. You can build interactive maps and produce [magnificent visualizations](https://www.r-graph-gallery.com/).


## _But I’m too old for this :(_

This graph summarizes why you should start learning R:

![image](https://user-images.githubusercontent.com/8527082/55494231-a94d0600-563a-11e9-816d-2bbfd6cab64f.png)
 
I can assure you that it is quite easy to reach the point where R surpasses the maximum reward you can get from SPSS, even if you start from an absolute zero. You do not need to learn all of the abovementioned stuff at one go; you learn a fundamental basis of R programming and then learn more advanced topics according to your needs.

## _Owkay, but I don’t know where to start :(_

There are literally countless free resources to learn R. This overload of information prevents most people from starting the journey. Hence, I only mention one handy (and quite concise) resource which I have recently found: Danielle Navarro’s [**R for Psychological Science**](https://psyr.org/)
https://psyr.org/ 
As the name says, it is tailored for psychology.

However, **for an even faster, more efficient learning,** you can also benefit from [RStudio cheat sheets](https://www.rstudio.com/resources/cheatsheets/) after you have the fundamental knowledge of R. I suggest to follow this order:
-    Base R
-    RStudio IDE Cheat Sheet
-    Data Import Cheat Sheet
-    Advanced R
-    Data Transformation Cheat Sheet
-    R Markdown Cheat Sheet
-    Data Visualization Cheat Sheet
-    Apply Functions Cheat Sheet 

Now that you are beginning, I very strongly suggest mastering packages `plyr` and `dplyr` so you do not look like a troglodyte to other R users. The former offers a better way of writing apply functions, and the latter is the best way of handling data very intuitively and efficiently with pipe operator (`%>%`) and its functions for data manipulation. You can get a good understanding of `plyr` in Hadley Wickham's [paper](https://www.jstatsoft.org/index.php/jss/article/view/v040i01/v40i01.pdf) in the Journal of Statistical Software (2011) or [this tutorial](https://seananderson.ca/2013/12/01/plyr/). For `dplyr`, benefit from Garrett Grolemund’s data wrangling tutorial ([webinar](https://www.rstudio.com/resources/webinars/data-wrangling-with-r-and-rstudio/) and [slides](https://github.com/rstudio/webinars/blob/master/05-Data-Wrangling-with-R-and-RStudio/wrangling-webinar.pdf)). 


**Also**, Google, Stack Overflow, and Stack Exchange are your allies. In 90-95% of the cases, you can find literally the exact pieces of code you need in less than a minute or two. If you couldn't find a proper answer to your question (or had difficulty understanding what you have discovered), simply ask it on [Cross Validated](https://stats.stackexchange.com), where a kind stranger will help you quite soon. Interestingly, you can cite questions and answers you find Stack Overflow and Stack Exchange; they give you BibTeX citation code.

![image](https://user-images.githubusercontent.com/8527082/55495100-760b7680-563c-11e9-8f3d-e04e10c1c6c3.png)

## _I’m super busy :( How long does it all take?_

This is one of the strongest excuses to postpone learning useful skills, whether it is about programming (learning another language, or practicing a [decent coding style](https://google.github.io/styleguide/Rguide.xml)), using a new tool (like git versioning), or acquiring more deepening your superficial theoretical background on a subject. One should always remember this lesson, that a King of Jerusalem, probably Solomon, draws from his experience:

>If the ax is dull and its edge unsharpened, more strength is needed, but skill will bring success.
-- (Ecclesiastes, 10:10)

![image](https://user-images.githubusercontent.com/8527082/55495515-5a54a000-563d-11e9-9486-3c321ddbeb02.png)

I think that Navarro’s tutorial should take less than a day or so. Also, you can quickly benefit from the cheat sheets when you need them. The data wrangling slides (dplyr) took me less than an hour (20-30 minutes?) to master, and plyr shouldn't be much different.

## Finally,

As a gift for reading this far, I would like to introduce [Ditto clipboard manager](https://ditto-cp.sourceforge.io/), a tool that helps you keep tens (or even hundreds) of copied/cut images and texts (also files!) in your clipboard with a very tiny overload on your PC. You can always search in the list, and you can use it as a draft pad. It takes few minutes to figure it out and you will soon wonder how you had managed to work with a computer without it.

> Fear God, and keep his commandments; for that is the whole duty of everyone
-- (Ecclesiastes, 12:13)