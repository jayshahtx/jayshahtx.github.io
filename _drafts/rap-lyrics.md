---
layout:     post
title:      Rap Lyrics, Feminism, Love, and Statistics
date:       2015-05-20
summary:    Mining 30 years of rap lyrics to find patterns
og_image:   /assets/jayshah_bike.png
---

I've listen to rap/hip-hop for most of my life and have always been amused by the lyrics. So few genres of music regularly transfer phrases into our everyday vocabulary ('bae' is the most recent example that comes to mind).

I wanted to statistically explore rap lyrics from the past 20 years to see if any trends emerged. Thanks to [Billboard](http://en.wikipedia.org/wiki/List_of_Billboard_number-one_rap_singles_of_the_1980s_and_1990s#1989) and [Rap Genius](http://rap.genius.com), I could assemble a corpus of lyrics from every song that made it to the top of the Hip Hop chart. As always, it took bloody forever to assemble a usable dataset. Below is a distribution for the number of songs that made it to the top each year.

<div>
    <a href="https://plot.ly/~jayshahtx/97/" target="_blank" title="#1 Billboard Rap Singles" style="display: block; text-align: center;"><img src="https://plot.ly/~jayshahtx/97.png" alt="#1 Billboard Rap Singles" style="max-width: 100%;"  onerror="this.onerror=null;this.src='https://plot.ly/404.png';" /></a>
    <script data-plotly="jayshahtx:97" src="https://plot.ly/embed.js" async></script>
</div>

You can quickly see that songs are staying at the top of the charts longer than they did twenty years ago. Let's dive in and find some more interesting patterns.

# All kinds of Bad Words

Rap is pretty notorious for its foul lyrics. One of the first questions I wanted to answer was how profanity has changed over time. It turns out that I'm not the first person to wonder this and some researchers over at CMU had assembled a corpus of 1300 expletives. The corpus was so unapologetically exhaustive that just reading through it made me feel like an awful person.

<div>
    <a href="https://plot.ly/~jayshahtx/85/" target="_blank" title="Expletives Per Songs" style="display: block; text-align: center;"><img src="https://plot.ly/~jayshahtx/85.png" alt="Expletives Per Songs" style="max-width: 100%;width: 936px;"  width="936" onerror="this.onerror=null;this.src='https://plot.ly/404.png';" /></a>
    <script data-plotly="jayshahtx:85" src="https://plot.ly/embed.js" async></script>
</div>

It's a little noisy, but it looks like rap has increased in its profanity. I was surprised by this trend, I distinctly recall very vulgar songs from the 90s. Perhaps profanity and vulgarity are not interchangeable. Let's cut the data differently.

# Misogyny isn't as cool as it used to be

Let's introduce a metric to guage how often women are referenced.Rappers casually reference girls' names in a sexually explicit or misogynistic way ([Petey Pablo](http://genius.com/Petey-pablo-freek-a-leek-lyrics) I'm looking at you). How often is a woman's name mentioned in a song?

<div>
    <a href="https://plot.ly/~jayshahtx/120/" target="_blank" title="Expletives, Female Names per Song" style="display: block; text-align: center;"><img src="https://plot.ly/~jayshahtx/120.png" alt="Expletives, Female Names per Song" style="max-width: 100%;width: 936px;"  width="936" onerror="this.onerror=null;this.src='https://plot.ly/404.png';" /></a>
    <script data-plotly="jayshahtx:120" src="https://plot.ly/embed.js" async></script>
</div>





