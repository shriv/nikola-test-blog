<!--
.. title: Geospatial analyses with R
.. slug: geospatial-analyses-with-r
.. date: 2019-07-29 18:00:15 UTC+12:00
.. tags:
.. category:
.. link:
.. description:
.. type: text
-->

## Introduction
The battle of R vs. Python for data science is a constantly raging one for practitioners. Many choose their side and stick to it vehemently but others, like me, flit from one side to another using the 'Whatever is best for problem at hand' excuse. I say 'excuse' because sometimes it feels like I'm simply biding my time for a clear winner to emerge. At other times, 'excuse' is the wrong word because I do truly feel like each has their strengths and cutting-edge tools and packages are not developed simultaneously in both ecosystems.

My first port of call is usually Python, even though I think dplyr (and the tidyverse) is far better than pandas. Python is an easy start because: (1) the syntax is easy, (2) verbose loops for lazy and quick coding aren't poorly performant (unlike R!) and, (3) you don't have to remember too many onliners / idioms. Reason (3) is touted as a major scoring point for R afficianados but when data science work spans across many domains, the suite of necessary packages (and idioms) grows substantially - a real travail for those of us with poor memory.

True to my preference my previous forays into analysing transport, specifically walking, have used the Python suite of geospatial and analysis packages e.g. geopandas, osmnx, pandana, pandas, numpy, seaborn and pystan. However, in less than a week, I'll be transitioning to a new employer whose data science will be driven by R. This imminent move has prompted a self-learning spike culminating in this literature review of R packages that support spatial analyses (particularly pertaining to transport).

 I hope to split this review into three main parts; starting with a focus on R tools, exploring the Python side and wrapping up with a comparison of the two ecosystems. The reason for this triple pronged approach links back to the introduction citing the asymmetry in functionality available in R vs. Python. I know there are other 'on the fence' Data Scientists so I'm hopeful that this review will save some time and effort in scouting out the best tool / ecosystem for geospatial analyses.

## Caveat Lector (Reader Beware)
A dramatic way of noting that this review is not intended to be a comprehensive one. I only consider the following geospatial analyses:

- Wrangling primitive geospatial data (points, lines, polygons)
- Street network analysis
- POIs and Accessibility
- Assigning and visualising transport flows
- Routing
- Wrangling GTFS

## Enter Robin Lovelace
A quick Google search will reveal that the lynchpin of knowledge, innovative work, and  package development in the R geospatial world is [Robin Lovelace](https://www.robinlovelace.net/). Singling Dr. Lovelace out is not meant to downplay the contributions of countless others but that he plays quite a central role in opening up the R geospatial world to a relative newbie. For example, much of this particular post is inspired by [Dr. Lovelace's talk at UseR2019](https://www.robinlovelace.net/presentations/user2019-r-for-transport-planning.html#1).
