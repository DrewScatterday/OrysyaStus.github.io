---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---
## Traffic Cruising
Vehicle cruising (individuals looking for parking and for-hire vehicles operating without a passenger) is a major contributor to traffic congestion in downtown Seattle. Still, the magnitude and location of vehicle cruising is poorly understood. To get a better understanding of where vehicles cruise, we propose a framework for using traffic sensor data. We generate most likely paths traversed through filtering out unrealistic behavior and incorporating routing. We break up individual trips via segmentation in terms of time and method of transportation. After segmentation, we introduce metadata to describe the trip and use a semi-supervised machine learning approach to label the data. Ultimately, we create an interactive heat map of downtown Seattle that can be used to visualize the relative levels of cruising.

This research has the potential to help transportation agencies, technology companies, and car companies predict the availability of parking and more accurately direct travelers with online, mobile, and connected tools, thereby reducing congestion impacts, emissions, and fuel costs.

* Data Science for Social Good Fellow (University of Washington, Microsoft, City of Seattle)
* [Code](https://github.com/OrysyaStus/TrafficCruising-DSSG2017), [Write Up](http://www.dssgfellowship.org/wp-content/uploads/2017/09/bejcek.pdf), [Microsoft Press Release](https://news.microsoft.com/features/students-create-something-really-incredible-broader-aim-help-two-cross-border-cities-thrive-together/), [Seattle King 5 News Press Release](https://www.king5.com/article/news/local/seattle/one-third-of-seattle-drivers-cruising-for-parking-rides-study-finds/281-465290202)<br />
<img src='/images/trafficCruising.PNG'>

## Basic Needs
Our SMS-based application provides access to routing, emergency, mental health, sanitation, education, location, weather, and feedback services to vulnerable populations without wifi dependency. Basic Needs addresses immediate needs, connects vulnerable populations to their needs, and initiates a dialog between cities and vulnerable populations for social engagement and improvement.

* Seattle AngelHack 2017 HERE Challenge Winner
* [Code](https://github.com/OrysyaStus/basicneeds), [Demo](https://www.youtube.com/watch?v=Rk4o2yFx9z0)<br />
[![video](https://img.youtube.com/vi/Rk4o2yFx9z0/0.jpg)](https://www.youtube.com/watch?v=Rk4o2yFx9z0)

## Breaking News
A collection of labeled fake news and real news (top credible news sources from https://webhose.io/) was used to train a Naive Bayes model to predict probabilities of fake news based on article text. The model predicted fake or real with 85% accuracy using ~1,100 articles in our testing set and a training set of ~4,000 articles. We cannot guarantee the correctness of our labels, given the subjectivity of the terms "fake" and "real". Therefore this tool is not a perfect judge of all articles, but can be used as a gentle guide.

* Seattle Global AI Hackaton Regional Winner June 2017
* [Code](https://github.com/OrysyaStus/fakenews), [Website](http://newsbreakers.herokuapp.com/)<br />
[![video](https://img.youtube.com/vi/misls7a1ePo/0.jpg)](https://www.youtube.com/watch?v=misls7a1ePo)

## Waste Bots Unleashed
We extracted a sample of 40 littered Google Street View San Diego images for training and sample of a random sample of ~50,000 Google Street View images across San Diego, California for testing, processed the data, trained shape recognition and color recognition models, classified our images based on each model as littered/not littered, and designed an interactive website for visualizing which zip codes in San Diego are least and most littered. The goal is to engage public and government officials in keeping San Diego beautiful. This is a prototype and shows the potential of using data science for public benefit.

* Grand Prize Winners at San Diego 2017 Women's Hackathon
* [Code](https://github.com/OrysyaStus/wastebotsunleashed.github.io), [Website](https://wastebotsunleashed.github.io/)<br />
<a href="http://wastebotsunleashed.github.io/">
<img src="https://OrysyaStus.github.io/images/wasteBotsUnleashed.png" alt="Go to Waste Bots Unleashed Website">
</a>

## San Diego Hearts
We designed an interactive website that examined the factors contributing to varying heart disease rates across San Diego to recommend ways to bring down the rates in the high risk areas. The goal is to help the potential users to make better decisions to run the campaigns and channelize the funds to the right regions.

* 2nd place at the 2017 San Diego Big Data Hackathon
* [Code](https://github.com/OrysyaStus/sandiegohearts.github.io), [Website](https://sandiegohearts.github.io/)<br />
<a href="https://sandiegohearts.github.io/">
<img src="https://OrysyaStus.github.io/images/sanDiegoHearts.png" alt="Go to San Diego Hearts Website">
</a>
