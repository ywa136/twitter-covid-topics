# twitter-covid-topics
Visalization of learned topics for the paper "A Geometry-Drive Longitudial Topic Model" submitted to HDSR by Y. Wang, C. Hougen, B. Oselio, W. Dempsey, A.O.Hero.

By default the main notebook `scripts/topicMatching.ipynb` loads learned topics and associated data from a folder *learned_topics*. This folder can be downloaded [here](https://www.dropbox.com/sh/kd9a0zptteq8vun/AAAHVGEFfz5Ko3_0g1RqLOLQa?dl=0). Note that in the data folder we have included learned topics from an extended period, i.e., May 15 to Aug 15, which was not included in the main paper. 

The notebook `scripts/TopicFlow.ipynb` loads the same set of learned topics, but assembles topic trends using the method called [TopicFlow](https://ieeexplore.ieee.org/document/6785782). The notebook `scripts/simulation_phate.ipynb` presents simulation studies for PHATE-Helliner dimensionality reduction.

An associated web application built by `shinyapp` is hosted [here](https://wayneyw.shinyapps.io/mrf_smooth_map_app) by James Chu and Yu Wang. The web app presents spatio-temporal visualization of the topic modelling results.
