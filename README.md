# Computer Vision - Road Damage Detection for multiple countries

For full explanation, visit my blog - 

## Overview:
Roads are the phenomenal source of not just the transportation and travel, but for so many things. And we all use roads, in order to follow our daily routines. Roads make a crucial contribution to economic development and growth, and bring important social benefits. They are of vital importance in order to make a nation grow and develop. In addition, providing access to employment, social, health and education services makes a road network crucial in fighting against poverty. Roads open up more areas and stimulate economic and social development. For those reasons, road infrastructure is the most important of all public assets.

The Road Network has a spread over multi-million miles. Hence maintaining roads becomes quite hectic for the governments and the local bodies (Municipalities). Every road needs maintenance after a few years, and this maintenance can have major financial impacts on the economy and citizens.

Now we need to know, how can we resolve the problem of road maintenance. So there are three ways to do so. 

**Manual Method -** This method is consider as a traditional method. In the ​Manual method, a team of investigators detects damages via walking or by sitting on a slow moving vehicle. This visual inspection suffered from the subjective judgement of investigators, and this process is very time consuming and not safe.

**Semi-automated Method -** This method is also consider as a traditional method. In the ​Semi-automated method, a fast moving vehicle is used to take pictures of the damages, but here again for crucial damages, manual inspection is needed. But ultimately this method is quite safe as compared to manual method, but not fully safe.

**Fully-automated Method -** This method is the modern method to check the damages. In the ​Fully automated method, a fast moving vehicle equipped with sophisticated and expensive sensors. Then the processing of collected images can be done through image processing and pattern recognition. But this method is too expensive because of the use of high quality sensors and cameras. So financially weak local bodies can't afford it.

Instead of using these high quality cameras and sensors, government and local bodies can use smartphones attached to the dashboard of the vehicle. This method is very affordable compared to prior methods. This work proposed by the researchers of the University of Tokyo. They attached a mobile phone on the vehicles dashboard to capture images, they used a special software, which can capture road images one per second and record location too, with the average vehicle speed of 40 km/h.

## Project Goal:
Since the idea is to mount the smartphone on the dashboard of a car, so ultimately we have to built a Real time object detector. And more specifically this system has to work in the mobile devices.

## Data:
**RDD2020 -** Since previous datasets just focused on a single country, Japan. So in order to check its feasibility new data has been added from India and Czech Republic. Now this ​RDD2020 contains 26620 images and annotations(damage description) from Japan, from India and from Czech Republic partially from Slovakia. Unlike previous versions this version has just 4 damage categories namely D00, D10, D20 and D40. The reason to exclude the rest of the 4 damage categories is because these issues can spread all over the country very normally and change from one country to another country.
There is one difference across all images is, the images from Japan and Czech Republic have 600X600 dimensions while the images from India have 720X720 dimensions. And this dataset is created in different lighting and weather conditions.

Data download link : https://github.com/sekilab/RoadDamageDetector

## Plateform:
Google Colab

## Models
- SSD Mobilenet v1
- YOLO v3

