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

![](/assets/post5_chart1.png)

You can quickly see that songs are staying at the top of the charts longer than they did twenty years ago. Let's dive in and find some more interesting patterns.

# All kinds of bad words

Rap is pretty notorious for its foul lyrics. One of the first questions I wanted to answer was how profanity has changed over time. It turns out that I'm not the first person to wonder this and some researchers over at CMU had assembled an [exhaustive] corpus of 1300 expletives.

![](/assets/post5_chart2.png)

It's fairly noisy, but it looks like rap has gradually increased in profanity over time. I was surprised by this trend, I distinctly recall very vulgar songs from the 90s. Perhaps profanity and vulgarity are not interchangeable. Let's cut the data differently.

# Misogyny isn't as cool as it used to be

Let's introduce a metric to guage how often women are referenced. Rappers casually reference girls' names in a sexually explicit or misogynistic way ([Petey Pablo](http://genius.com/Petey-pablo-freek-a-leek-lyrics) I'm looking at you). How often is a woman's name mentioned in a song?

![](/assets/post5_chart3.png)

Interestingly, women are referenced much less frequently in today's music than that of 20 years ago while profanity has played a consistent role in rap songs. Could this change be attributed to a difference in gender of top rap artists? After all, female artists probably wouldn't talk about other females like men do...

![](/assets/post5_chart4.png)

I added a chart which includes the percent of top artists that were female each year. Look carefully at the two graphs, can you spot a trend? At first, it appears that the presence of female rappers is inversely related to the use of female names - a pattern that would make sense. But then in years like 2002 and 2005, female artists appear to be postively related to female names.

This is the problem with rap lyrics - it is incredibly difficult to characterize years of complicated language and culture by simple statistics. Before settling with this graph, I explored the data in numerous ways to see if any patterns emerged. I wanted to include this chart because sometimes trends don't exist in places we expect them to.

# The rap game's softest players

It seems the jury is still out on whether it's acceptable for rappers to be in touch with their sentimental side. Drake is consistently made fun for being sentimental, yet he shattered records with [impressive sales numbers](http://en.wikipedia.org/wiki/Drake_discography). After the blunts have been exchanged, alcohol consumed, and currency accounted for, is it really cool to be an emotional monogamist? To answer this question, I wanted to see how rappers use the word "love" in their lyrics and contrast it to their perception.

The graph below looks at what rappers state they "love" the most in their 5 most popular songs. For example, 20% of the time Twista uses the word "love", he follows it with "me". The other 80% is used to say he loves inanimate objects (clothes, money, etc).

![](/assets/post5_chart5.png)

True to his reputation, Drake tops the list as the softest rapper with 100% of his use of the word "love" referencing either himself or another person. Lil' Wayne, on the other hand, loves himself about 60% of the time (as evidenced in his hit single B****** Love Me) but never another person. Jay-Z appears to strike a good balance of respecting himself and loving (presumably) Queen B with a respectable split of 10% loving her and 30% loving himself.

# Parting thoughts

While I enjoyed exploring the data, I am not surprised at my (mostly) inconclusive results. You could assemble a hundred interesting graphs from these lyrics and you'd still be hard pressed to find unifying themes across this genre of music. In my opinion, that is the beauty in rap music. So much of it is so dense, up for intepretation, and worthy of analysis that there is rarely a conclusive resolution in discussion of lyrics. How has Nikki Minaj changed the role of women in the rap industry? What do Drake's emotional lyrics suggest about this generation of listeners? Making graphs and cutting the data is always fun, but answering questions like these will take a lot more than a few regressions and trend lines.









