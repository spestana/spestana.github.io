---
layout: post
title:  "Waterhackweek 2020"
---


# Waterhackweek 2020
*Sept. 2020*

## Tutorials: Gridded data & statistics

I gave two tutorials at Waterhackweek, one which covered working with gridded data using [xarray](https://xarray.pydata.org/en/stable/), the other introducing some statistics workflows with [scipy](https://www.scipy.org/) functions:
 * **Waterdata** - Access and analyze raster and multi-dimensional gridded data: [GitHub](https://github.com/waterhackweek/waterdata) , [YouTube](https://youtu.be/37HdGuL9m-s)
 * **Waterstats** - Statistics with water data, hypothesis testing, linear regression: [GitHub](https://github.com/waterhackweek/waterstats) , [YouTube](https://youtu.be/a5uCj1mX7Qs)

## Project: Fire & Water

For the hackathon project, our team used thermal infrared imagery from the NASA JPL [ECOSTRESS](https://ecostress.jpl.nasa.gov/) instrument and NASA [MODIS products](https://developers.google.com/earth-engine/datasets/catalog/modis) to look at surface temperature and chlorophyll-a changes for [Clear Lake](https://www.fws.gov/refuge/Clear_Lake/) in northern California, before and after an adjacent fire in 2019.

![ECOSTRESS animation Clear Lake](/assets/images/eco-clearlake.gif)

We used open-source python and jupyter notebooks, and cloud-computing resources provided by [CUAHSI](https://www.cuahsi.org/), to develop a workflow with the ECOSTRESS images: extracting a time series of surface temperatures from within the boundaries of a shapefile before and after the [2019 Tucker Fire](https://www.fire.ca.gov/incidents/2019/7/28/tucker-fire/). ECOSTRESS data was accessed throu the NASA/USGS/LPDAAC [AppEEARS web interface](https://lpdaacsvc.cr.usgs.gov/appeears/).

![Screenshot of ECOSTRESS jupyter notebook](/assets/images/eco-jupyter.jpg)

We also learned how to use the [Google Earth Engine python API](https://developers.google.com/earth-engine/guides/python_install-conda) to retrieve several years of MODIS observations of surface temperature, reflectance, and gross primary production. [This guide was very helpful](https://towardsdatascience.com/modis-vegetation-indices-a-gee-approach-f48e1259e462).

![timeseries plots of MODIS NDVI and false color](/assets/images/modis-clearlake.jpg)

[**View the hackathon project files on GitHub**](https://github.com/waterhackweek/whw2020_firewater)

[Read more about Waterhackweek here](https://www.ce.washington.edu/news/article/2020-09-17/waterhackweek-applying-data-science-water-challenges)

---

Update: In the summer of 2021, about a year after the hackweek, I was able to visit Clear Lake in person!

![Steven at Clear Lake](/assets/images/stevenclearlake.jpg)

