---
layout:     post
title:      Rap, Feminism, Love, and Statistics
date:        
summary:    Mining 30 years of rap lyrics to find patterns
og_image:   /assets/jayshah_bike.png
---

I've listen to rap/hip-hop for most of my life and have always been amused by the lyrics. So few genres of music regularly transfer phrases into our everyday vocabulary ('bae' is the most recent example that comes to mind).

I wanted to statistically explore rap lyrics from the past 20 years to see if any trends emerged. Thanks to [Billboard](http://en.wikipedia.org/wiki/List_of_Billboard_number-one_rap_singles_of_the_1980s_and_1990s#1989) and [Rap Genius](http://en.wikipedia.org/wiki/List_of_Billboard_number-one_rap_singles_of_the_1980s_and_1990s#1989), I could assemble a corpus of lyrics from every song that made it to the top of the Hip Hop chart. As always, it took bloody forever to assemble a usable dataset. Below is a distribution of songs that made it to the top each year.

<div>
    <a href="https://plot.ly/~jayshahtx/97/" target="_blank" title="#1 Billboard Rap Singles" style="display: block; text-align: center;"><img src="https://plot.ly/~jayshahtx/97.png" alt="#1 Billboard Rap Singles" style="max-width: 100%;"  onerror="this.onerror=null;this.src='https://plot.ly/404.png';" /></a>
    <script data-plotly="jayshahtx:97" src="https://plot.ly/embed.js" async></script>
</div>

You can quickly see that songs are staying at the top of the charts longer than they did twenty years ago. Let's dive in and find some more patterns.

# All Kinds of Bad Words

Rap is pretty notorious for its foul lyrics. One of the first questions I wanted to answer was how profanity has changed over time. It turns out that I'm not the first person to wonder this and some researchers over at CMU had assembled a corpus of 1300 expletives. The corpus was unapologetically exhaustive and just reading the CSV file made me feel like an awful person.




