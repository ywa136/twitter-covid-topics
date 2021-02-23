# twitter-covid-topics
Visalization of learned topics for the paper "A Geometry-Drive Longitudial Topic Model" submitted to HDSR by Y. Wang, C. Hougen, B. Oselio, W. Dempsey, A.O.Hero.

By default the notebook `scripts/topicMatching.ipynb` loads learned topics and associated data from a folder *learned_topics*. This folder can be downloaded [here](https://www.dropbox.com/sh/kd9a0zptteq8vun/AAAHVGEFfz5Ko3_0g1RqLOLQa?dl=0). The notebook `TopicFlow.ipynb` loads the same set of learned topics, but assembles topic trends using the method called [TopicFlow](https://ieeexplore.ieee.org/document/6785782).

An associated web application built by `shinyapp` is hosted [here](https://wayneyw.shinyapps.io/mrf_smooth_map_app/?_ga=2.193982824.491438872.1614044067-1870480178.1613069761) by James Chu and Yu Wang. The web app presents spatio-temporal visualization of the topic modelling results.
