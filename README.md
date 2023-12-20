# AI-in-Data-Science-Data-Challenge
Solution to the Data Challenge task. Authors are Izabell Járó, Kristóf Benedek, and Marcell Emmer.

Computer vision is one of the most promising fields of data science since it has a wide
range of applications including self-driving cars, medical image analysis, and facial recognition. 
The Data Challenge aims to provide hands-on experience in digital image
processing.

Our task is to build an algorithm for prohibitory traffic sign recognition. Some of the possible ways of getting images:

* It is possible to simply take screenshots of the desired images (e.g. Google Street View
or other online sources).
* You can use the google-streetview [Python module](https://pypi.org/project/google-
streetview/) for downloading Google Street View images with a Python script. Details
about the usage of Google Street View API can be found in the [official documentation](https://developers.google.com/maps/documentation/streetview/intro).
* Use some already existing datasets, augment it, label it, etc 

There are 6 traffic sign categories your model should be able to recognize:



You can reach the database [here](https://mega.nz/file/eo9VHLRT#MFZRQKcUySyg1H9q3-9IgcS0T6OBx-kBcgE1z7RrPZ0). It contains 6 different classes of prohibitory traffic signs. It was compiled from the [GTSRB](https://benchmark.ini.rub.de/gtsrb_news.html) and [TSRD](http://www.nlpr.ia.ac.cn/pal/trafficdata/recognition.html) databases. It is already split into a training and testing dataset. Preprocessing and data augmentation are needed, these are just the raw source files.
