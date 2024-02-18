+++
title = "Analysing sleeping data from Mi 3 band"

date = 2018-11-23
lastmod = 2018-11-24
draft = true

summary = "Using ggplot2 to visualize sleeping data"

[[gallery_item]]
album = "1"
image = "https://raw.githubusercontent.com/gcushen/hugo-academic/master/images/theme-default.png"
caption = "Default"

[[gallery_item]]
album = "1"
image = "https://raw.githubusercontent.com/gcushen/hugo-academic/master/images/theme-ocean.png"
caption = "Ocean"

[[gallery_item]]
album = "1"
image = "https://raw.githubusercontent.com/gcushen/hugo-academic/master/images/theme-dark.png"
caption = "Dark"

[[gallery_item]]
album = "1"
image = "https://raw.githubusercontent.com/gcushen/hugo-academic/master/images/theme-forest.png"
caption = "Default"

[[gallery_item]]
album = "1"
image = "https://raw.githubusercontent.com/gcushen/hugo-academic/master/images/theme-coffee-playfair.png"
caption = "Coffee theme with Playfair font"

[[gallery_item]]
album = "1"
image = "https://raw.githubusercontent.com/gcushen/hugo-academic/master/images/theme-1950s.png"
caption = "1950s"
+++

With the advent of wearable devices, we now have the ability to collect a wide range of personal health and lifestyle data, giving us the opportunity to take a closer look like what our lifestype look like.

Mi 3 Fit band, for instance, collects users' sleep data by recording how actively they are moving, and uses this information to decide whether the user is in light or deep sleep or somber. The MiFit software also calculates a sleeping quality score, which is intuitive and easy to interpret. Here I analyse the sleeping data collected from my Xiaomi Mi 3 Fit band with some basic data visualization techniques in ggplot2.

### Read data

```{r}

```

First, I plotted the sleep quality score against date. It can be seen that there is a significant increase in the 

![](/img/blog/date-score.png)
