---
layout:     post
title:      Rap Lyrics, Feminism, Love, and Statistics
date:       2015-06-02
summary:    A statistical analysis of 25 years of rap lyrics
og_image:   /assets/post5_chart5.png
---

For a genre of music that is so casually dismissed as unintellectual, rap lyrics have been obsessively analyzed by academics, fans, and enthusiasts for decades. As an avid fan of rap music myself, I wanted to see if I could find any interesting patterns in lyrics from the past twenty years. After months of procrastinating this blog post, I finally buckled down to see what stories the data told.

# Collecting data

Thanks to historical [Billboard charts](http://en.wikipedia.org/wiki/List_of_Billboard_number-one_rap_singles_of_the_1980s_and_1990s#1989) and [Rap Genius](http://rap.genius.com), I could assemble a corpus of lyrics from every song that made it to the top of the Hip Hop chart since 1989. As always, it took bloody forever to assemble a usable dataset. Below is a distribution for the number of songs that made it to the top of the Billboard charts each year.

![](/assets/post5_chart1.png)

You can quickly see that songs are staying at the top of the charts longer than they did 25 years ago. Let's dive in and find some more interesting patterns.

# All kinds of bad words

Rap is pretty notorious for its foul lyrics. One of the first questions I wanted to answer was how profanity has changed over time. It turns out that I'm not the first person to wonder this and some researchers over at CMU had assembled an [exhaustive] corpus of 1300 expletives.

![](/assets/post5_chart2.png)

It's fairly noisy, but it looks like rap has gradually increased in profanity over time. Could the same be said for vulgarity?

# Misogyny isn't as cool as it used to be

Let's introduce a metric to guage how often women are referenced. Rappers casually reference girls' names in a sexually explicit or misogynistic way ([Petey Pablo](http://genius.com/Petey-pablo-freek-a-leek-lyrics) I'm looking at you). How often is a woman's name mentioned in a song? Below is the same graph as before with an added orange line representing the average number of female names per song.

![](/assets/post5_chart3.png)

Interestingly, women are referenced much less frequently in today's music than that of 20 years ago while profanity has played a consistent role in rap songs. Could this change be attributed to a difference in gender of top rap artists? After all, female artists probably wouldn't talk about other females the way men do.

![](/assets/post5_chart4.png)

I added a chart which includes the percent of top artists that were female each year. Look carefully at the two graphs, can you spot a trend? At first, it appears that the presence of female rappers is inversely related to the use of female names, a pattern that would make sense. But then in years like 2002 and 2005, female artists appear to be postively related to female names.

This is the problem with rap lyrics - it is incredibly difficult to characterize years of complicated language and culture by simple statistics. Before settling with this graph, I explored the data in numerous ways to see if any clear patterns emerged. I wanted to include this chart because sometimes trends don't exist in places we expect them to.

# The rap game's softest players

It seems the jury is still out on whether it's acceptable for rappers to be in touch with their sentimental side. Drake is consistently made fun for being sentimental, yet he has shattered records with [impressive sales numbers](http://en.wikipedia.org/wiki/Drake_discography). After the blunts have been exchanged, alcohol consumed, and currency accounted for, is it really cool to be an emotional monogamist? To answer this question, I wanted to see how rappers use the word "love" in their lyrics and contrast it to their perception.

The graph below looks at what rappers state they "love" the most in their 5 most popular songs, highlighting the likelihood that the word "love" is followed by either "you" or "me" in their lyrics. For example, 20% of the time Twista uses the word "love", he follows it with "you". The rest of the time, it's followed by words othern than "me" or "you" (IE: "I love money", etc).

![](/assets/post5_chart5.png)

True to his reputation, Drake tops the list as the softest rapper with 100% of his use of the word "love" referencing either himself or another person. Lil' Wayne, on the other hand, loves himself about 60% of the time (as evidenced in his hit single B****** Love Me) but never another person. Jay-Z appears to strike a good balance of respecting himself and loving (presumably) Queen B with a respectable split of 10% loving her and 30% loving himself.

# Parting thoughts

While I enjoyed exploring the data, I am not surprised at my (mostly) inconclusive results. I could assemble a hundred interesting graphs from these lyrics and I'd still be hard pressed to find unifying themes across this genre of music. While the density of rap lyrics allows opponents to easily miss its merit, rap's contentious prose is probably its most attractive attribute.

So much of it is opaque, up for intepretation, and worthy of analysis that discussions of lyrics rarely end in resolution. Whose lyrics have pushed the agenda for feminism more, Nicki Minaj or Beyonce? What do Drake's emotional themes suggest about this generation of listeners? Making graphs and cutting the data is always fun, but answering questions like these will take a lot more than a few regressions and trend lines.

<br>







