---
layout:     post
title:      Can an Algorithm Identify Student Leaders on Campus?
date:       2012-12-27 
summary:    Crawling my university's website to find my most popular friend
---

Is it possible to identify student leaders based on how much they are mentioned on the university website? After all, the more a student impacts the school, the more likely they are to be mentioned on the internet, right? Right.

Of course, this is a very naïve way to measure impact, but I wanted to familiarize myself with spidering and text tokenization/processing. Why not find some interesting data at the same time? With code largely adopted from Dr. Raymond Mooney’s [Information Retrieval course](http://www.cs.utexas.edu/~mooney/ir-course/), I spidered 20,000 pages from the McCombs School of Business website and looked for the names of members in the [Undergraduate Business Council](https://my.mccombs.utexas.edu/BBA/Student-Life/UBC). The results were interesting to say the least.

The program output included:

1. Number of times each student was mentioned
2. Year(s) each student was mentioned
3. Which part of the McCombs website the student was mentioned in (MPA Blog vs McCombs News vs Business Honors page, etc)

## First glance: Who was mentioned the most?

The most obvious way to interpret the results is simply to see who was mentioned the most. These rankings were unsurprising and surprising (Jamal) at the same time – the top 15 ranks are below:

![](/assets/post1_chart1.png)

As you probably noticed, the amount of times a student was mentioned quickly declines after the top 5 results. Even more obvious is Jamal’s astounding 955 mentions. After further investigation, it appears that Jamal’s name appears on every MPA Blog post, even those he didn’t author. For this reason, we will exclude Jamal from the dataset (sorry Jamal).

But it doesn’t make sense to look at just the number of times a student was mentioned – what about the year they were mentioned? What if the student was mentioned in different parts of the McCombs website – wouldn’t that mean the student is active in different parts of the school? Let’s revisit the way we rank each student.

## Take two: quality not quantity

I ranked the students again, but this time we introduce two more parameters (in addition to number of mentions) and combine them to assign a “score” to each person.

The first parameter is the years in which the student was mentioned – I specifically looked for a time stamp on each webpage and if I couldn’t find one, I marked the student reference as “undated”. The more years a student is mentioned in, the higher their “Year Score”.

The second data point is which subdirectories a person was mentioned in on the McCombs website – there are several portions ranging from blogs, updates from staff/faculty, and student news. The more portions a student was mentioned in, the higher their “URL score”.

![](/assets/post1_chart2.png)

Click the picture below to see the top 15 ranks as per the newly calculated “cumulative score”.

![](/assets/post1_chart3.png)

Only 1 person changes ranks – what gives? It appears the number of mentions is strongly correlated with years mentioned/categories mentioned in. Therefore, combining the 3 parameters doesn’t yield drastically different results.

While the top 15 ranks didn’t change much, multiple students changed ranks after the top 20 slots. The following students changed rank, indicating the new score was good at finding leaders that weren’t mentioned extremely often online. The following students increased in rank after the new score:

- Casey Shirley
- Alan Goldstein (2010-2011 President)
- Connie Tao (2011-2012 Executive Board)

## Evaluating "impact" of UBC Executive Board ('10'-'12')

Are students elected to executive board because of their impact on the school? Or do they impact the school only after being elected? Which comes first – election or impact?

To answer this question, I tallied up mentions the year before and after a student’s term on the executive board. The data is as follows:

![](/assets/post1_chart4.png)

The data suggests that students receive much more attention (more than double) on the McCombs website after being elected on the executive board, implying most of the impact is made after election.

![](/assets/post1_chart5.png)

Ultimately, this is a far from a perfect way to measure impact and only observes a small subset of students. There are many ways I can think of expanding this study, but in the interest of time (and desire to pursue other projects), I limited myself to the information you see on this page. Some other interesting patterns:

- McCombs has significantly increased how much online content it publishes in the past few years, meaning the “impact” (number of mentions) of alumni from 2011 and before is probably understated

- Because students are usually mentioned ~1 year after any major accomplishment/impact to the school, this data does a poor job of identifying current student leaders (most of the top ranked students have already graduated)

I hope you found this data somewhat interesting, particularly if you are in the organization. If you’d like to ask me questions, or see a particular element in the original data set, please comment below or shoot me an email! I have indexed all the URLs each person was mentioned in (even all of Jamal’s 955 mentions).
