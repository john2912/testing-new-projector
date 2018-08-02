---
title: New Test Video
key: d56e2187f5dffff1aa4b0ce5f28ce81b
video_link: https://videos.datacamp.com/transcoded/1796_intro-stats-eda/v1/hls-ch0_0.master.m3u8

--- type:TitleSlide key:8ca3021ecf
## New Test Video

*** =lower_third
name: Louis Bailey 
title: Instructor

*** =script


--- type:FullSlide key:88c4096d7b
## Test 2 columns

*** =part1
```{r}
ggJitter <- ggplot(bus, aes(x = MilesOneWay, y = Bus)) +
  geom_jitter(width = 0, height = 0.05)
``` {{1}}

```{r}
  print(ggJitter)
``` {{1}}


*** =script

