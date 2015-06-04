---
layout:     post
title:      Rap Lyrics, Feminism, Love, and Statistics
date:       2015-05-20
summary:    Mining 20 years of rap lyrics to find patterns
og_image:   /assets/jayshah_bike.png
---

For a genre of music that is so casually dismissed as unintellectual, rap lyrics have been obsessively analyzed by academics, fans, and enthusiasts for decades. As an avid fan of rap music myself, I wanted to see if I could find any interesting patterns in lyrics from the past twenty years. After months of procrastinating this blog post, I finally buckled down to see what stories the data told.

# Collecting data

Thanks to historical [Billboard charts](http://en.wikipedia.org/wiki/List_of_Billboard_number-one_rap_singles_of_the_1980s_and_1990s#1989) and [Rap Genius](http://rap.genius.com), I could assemble a corpus of lyrics from every song that made it to the top of the Hip Hop chart since 1989. As always, it took bloody forever to assemble a usable dataset. Below is a distribution for the number of songs that made it to the top each year.


<div>
    <a href="https://plot.ly/~jayshahtx/97/" target="_blank" title="#1 Billboard Rap Singles" style="display: block; text-align: center;"><img src="https://plot.ly/~jayshahtx/97.png" alt="#1 Billboard Rap Singles" style="max-width: 100%;"  onerror="this.onerror=null;this.src='https://plot.ly/404.png';" /></a>
    <script data-plotly="jayshahtx:97" src="https://plot.ly/embed.js" async></script>
</div>

You can quickly see that songs are staying at the top of the charts longer than they did twenty years ago. Let's dive in and find some more interesting patterns.

# All kinds of bad words

Rap is pretty notorious for its foul lyrics. One of the first questions I wanted to answer was how profanity has changed over time. It turns out that I'm not the first person to wonder this and some researchers over at CMU had assembled an [exhaustive] corpus of 1300 expletives.

<div>
    <a href="https://plot.ly/~jayshahtx/85/" target="_blank" title="Expletives Per Songs" style="display: block; text-align: center;"><img src="https://plot.ly/~jayshahtx/85.png" alt="Expletives Per Songs" style="max-width: 100%;width: 936px;"  width="936" onerror="this.onerror=null;this.src='https://plot.ly/404.png';" /></a>
    <script data-plotly="jayshahtx:85" src="https://plot.ly/embed.js" async></script>
</div>

It's a fairly noisy, but it looks like rap has gradually increased in profanity over time. I was surprised by this trend, I distinctly recall very vulgar songs from the 90s. Perhaps profanity and vulgarity are not interchangeable. Let's cut the data differently.

# Misogyny isn't as cool as it used to be

Let's introduce a metric to guage how often women are referenced. Rappers casually reference girls' names in a sexually explicit or misogynistic way ([Petey Pablo](http://genius.com/Petey-pablo-freek-a-leek-lyrics) I'm looking at you). How often is a woman's name mentioned in a song?

<div>
    <a href="https://plot.ly/~jayshahtx/120/" target="_blank" title="Expletives, Female Names per Song" style="display: block; text-align: center;"><img src="https://plot.ly/~jayshahtx/120.png" alt="Expletives, Female Names per Song" style="max-width: 100%;width: 936px;"  width="936" onerror="this.onerror=null;this.src='https://plot.ly/404.png';" /></a>
    <script data-plotly="jayshahtx:120" src="https://plot.ly/embed.js" async></script>
</div>

Interestingly, women are referenced much less frequently in today's music than that of 20 years ago while profanity has played a consistent role in rap songs. Could this change be attributed to a difference in gender of top rap artists? After all, female artists probably wouldn't talk about other females like men do...

<div>
    <a href="https://plot.ly/~jayshahtx/125/" target="_blank" title="Female References per Song, Percent of Hits by Female Artist" style="display: block; text-align: center;"><img src="https://plot.ly/~jayshahtx/125.png" alt="Female References per Song, Percent of Hits by Female Artist" style="max-width: 100%;width: 936px;"  width="936" onerror="this.onerror=null;this.src='https://plot.ly/404.png';" /></a>
    <script data-plotly="jayshahtx:125" src="https://plot.ly/embed.js" async></script>
</div>

I added a chart which includes the percent of top artists that were female each year. Look carefully at the two graphs, can you spot a trend? At first, it appears that the presence of female rappers is inversely related to the use of female names - a pattern that would make sense. But then in years like 2002 and 2005, female artists appear to be postively related to female names.

This is the problem with rap lyrics. It is incredibly difficult to characterize years of complicated language by simple statistics. Before settling with this graph, I had explored the data in numerous ways to see if any patterns emerged. I wanted to include this chart because sometimes trends don't exist in places we expect them to.

# The rap game's lousiest lover






