# ADS Project 1:  R Notebook on Lyrics Analysis

## Doc folder

The doc directory contains the report or presentation files. It can have subfolders. 

The file Text_Processing.Rmd contains code that deals with original dataset lyrics.Rdata, and Project1_ch3379 performs the whole analysis over the developing trend of song lyrics.

## Data story

### Lyric length
We split the time slot into two parts: before 2000(including 1970s, 1980s and 1990s) and 2010s, which represents classical music annd modern music style.

As the plots demonstrate, we find that Indie lyrics is the smallest part among all lyric styles. They did not appear before 2000, and accounts for the least percentage over all lyrics in 2010s.

Looking into the length distribution among different types of lyrics, we could find that the most lyric lengths are less than 1000, and the longest lyrics belong to Rock and Hip-hop. For most types, the lyric lengths have an uniform distribution over 0-1000 words; while Rock and Pop seem to have more short lengths(around 0-300). 

Referring to different time periods, we could find that the overall lyric length distribution is almost the same.

### Lyric Emotions
Sentiment Analysis on lyrics could show what kind of emotion they perform.

Lyric emotions before 2000 and on 2010s have nearly the same distribution. Two graphs both tell us that joy, anticipation and trust appear most on lyrics, while anger, surprise and disgust are the least frequent. That might beacuse the popular songs intend to express "positive" feelings and try to bring listeners more joy.

Looking carefully, we might observe that the frequency of different emotions becomes closer on 2010s compared to past times. The index of joy, anticipation and trust slightly drop, but fear, surprise and disgust(which would be seen as "negative" feelings) appear more on 2010s. That might reflect on the "social trends": People tend to be more complex and under more pressure.

### "Radical" Metal Lyrics
By the clustering of emotions hidden in different lyrics, lyric styles that perform similar emotions would be regarded as "similar kind", and might have similar listeners. As Metal is far away from other styles, we could say that Metal is quite different from other types of lyrics.

When only looking into metal lyrics, the emotions expressed by metal are mostly fear, sadnness and anger, which is totally opposite from overall emotions. That tells us that metal could be seen as a kind of "radical" music, and the lyrics would express "bad" emotions bravely and undisguisedly.
