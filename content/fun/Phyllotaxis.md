+++
title = "Phyllotaxis with R"

date = 2018-08-10
lastmod = 2018-09-04
draft = false

summary = "Using R to plot phyllotaxis patterns inspired by Datacamp."

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

Phycllotaxis is a kind of 'seemingly' complex geometric pattern that looks complex but with very simple mathematics behind. It is not uncommon in nature. According to Wikipedia, phycllotaxis "is the arrangement of leaves on a plant stem" in botany. The following code show how to draw phycllotaxis patterns using ggplot2. The code was modified from a Project called *PHYLLOTAXIS: DRAW FLOWERS USING MATHEMATICS* on [Datacamp](www.datacamp.com).

```{r}
library(tidyverse)
library(ggplot2)

angle <- 31*pi/180
points <- 900

t <- (1:points)*angle
x <- sin(t)
y <- cos(t)

df <- data.frame(t, x, y)

options(repr.plot.width = 4, repr.plot.height = 4)
p <- ggplot(df, aes(x*t, y*t))
p + geom_point(alpha = 0.8, color = rainbow(points), shape = 16) +
    theme(title = element_blank(),
        panel.grid = element_blank(),
        axis.ticks = element_blank(),
        axis.text = element_blank(),
        panel.background = element_rect(fill = "white"),
        legend.position = "none")
```
The resulting figure looks like:
![phyllotaxis](/img/phyllotaxis.png)

By changing the two parameters `angle` and `points` in the code above, one can get endless number of phyllotaxis patterns.
