---
title: MetaboTS
subtitle: Visualisation framework for metabolic time-series data
image: assets/img/portfolio/05_metabots_full.jpg
alt: Time series shinyapp

caption:
  title: MetaboTS
  subtitle: Visualisation framework for metabolic time-series data
  thumbnail: assets/img/portfolio/05_metabots_thumb.jpg
---

I have started this project to help a colleague to analyze time-series data for free wheel running protocol for mice experiments and then extended it to monitoring of metabolic cages as well. You can find the shinyapps of legacy projects [here](https://icervenka.shinyapps.io/clams_vis/) and [here](https://github.com/icervenka/fwrvis_legacy). In the meantime a nice app [calR](https://calrapp.org/) was released that can process the metabolic cage data, but lacks some of the functionalites that I would like, such as parameter correlation or binning of different frequencies, so I continue to develop my own solution. The original software connected to the mice running wheels had several issues, including bugs in time measurement/conversion and tendency to shut down from time to time so I developed a python project that is able to deal with irregular time series and interpolate missing measurements so it can be properly visualized. Also new equipments were bought in the meantime, so it's nice to have a program that can unify the output formats from different sources. You can find the [conversion scripts](https://github.com/icervenka/clams_convert) and [visualisation framework](https://github.com/icervenka/clamsvis) in my Github.

{:.list-inline}
- Date: 2017
- Category: Data Visualisation