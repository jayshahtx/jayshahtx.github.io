---
layout:     post
title:      Can an Algorithm Identify Student Leaders on Campus?
date:       2012-12-27 
summary:    Crawling my university's website to find my most popular friend
---

Is it possible to identify student leaders based on how much they are mentioned on the university website? After all, the more a student impacts the school, the more likely they are to be mentioned on the internet, right? Right.

<br>
Of course, this is a very naïve way to measure impact, but I wanted to familiarize myself with spidering and text tokenization/processing. Why not find some interesting data at the same time? With code largely adopted from Dr. Raymond Mooney’s [Information Retrieval course](http://www.cs.utexas.edu/~mooney/ir-course/), I spidered 20,000 pages from the McCombs School of Business website and looked for the names of members in the [Undergraduate Business Council](https://my.mccombs.utexas.edu/BBA/Student-Life/UBC). The results were interesting to say the least.

<br>
The program output included:

1. Number of times each student was mentioned
2. Year(s) each student was mentioned
3. Which part of the McCombs website the student was mentioned in (MPA Blog vs McCombs News vs Business Honors page, etc)


