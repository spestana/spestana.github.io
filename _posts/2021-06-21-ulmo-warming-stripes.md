---
layout: post
title:  "Warming (climate) stripes in python with ulmo"
---


# Warming (climate) stripes in python with ulmo
*June 2021*

[Warming (or climate) stripe](https://en.wikipedia.org/wiki/Warming_stripes) figures are a striking way to visualize climate change and its signature in temperature trends, whether global or local.

Inspired by a matplotlib [blog post by Maximilian Nöthe](https://matplotlib.org/matplotblog/posts/warming-stripes/), I wanted to connect this visualization with a data source for the United States. 

The  python package [ulmo](https://github.com/ulmo-dev/ulmo) includes readers for [NASA DayMet](https://daymet.ornl.gov/) products.

DayMet provides daily climate variables for North America at 1 km spatial resolution going back about 40 years. 

While this time series isn't as long as used in most warming stripes figures, the spatial resolution would allow you to create unique warming stripe figures for different locations across North America.

The [repository here](https://github.com/spestana/ulmo-warming-stripes) contains a jupyter notebook that demonstrates reading DayMet data via ulmo, given a latitude and longitude of interest, and generating a warming stripes visualization for that location.

![warming stripes for Seattle, WA](https://raw.githubusercontent.com/spestana/ulmo-warming-stripes/main/warming-stripes-seattle.jpg "warming stripes seattle")

Also see [this web app version](https://share.streamlit.io/dhaitz/ulmo-warming-stripes/main/app.py) by [Dominik Haitz](https://dhaitz.github.io/).