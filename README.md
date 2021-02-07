# Computer Vision - Road Damage Detection for multiple countries

For full explanation, visit my blog - https://chamoli-619rahul.medium.com/computer-vison-road-damage-detection-for-multiple-countries-c4ce4fa1b7b8

## Overview:
Roads are the phenomenal source of not just the transportation and travel, but for so many things. And we all use roads, in order to follow our daily routines. Roads make a crucial contribution to economic development and growth, and bring important social benefits. They are of vital importance in order to make a nation grow and develop. In addition, providing access to employment, social, health and education services makes a road network crucial in fighting against poverty. Roads open up more areas and stimulate economic and social development. For those reasons, road infrastructure is the most important of all public assets.

The Road Network has a spread over multi-million miles. Hence maintaining roads becomes quite hectic for the governments and the local bodies (Municipalities). Every road needs maintenance after a few years, and this maintenance can have major financial impacts on the economy and citizens.

Now we need to know, how can we resolve the problem of road maintenance. So there are three ways to do so (brief explanation is in the blog). 

**Manual Method**
**Semi-automated Method**
**Fully-automated Method**

## Project Goal:
Since the idea is to mount the smartphone on the dashboard of a car, so ultimately we have to built a Real time object detector. And more specifically this system has to work in the mobile devices.

## Data:
**RDD2020 -** Since previous datasets (RDD2019) just focused on a single country, Japan. So in order to check its feasibility new data has been added from India and Czech Republic. Now this ​RDD2020 contains 26620 images and annotations(damage description) from Japan, from India and from Czech Republic partially from Slovakia. Unlike previous versions this version has just 4 damage categories namely D00, D10, D20 and D40. The reason to exclude the rest of the 4 damage categories is because these issues can spread all over the country very normally and change from one country to another country.
There is one difference across all images is, the images from Japan and Czech Republic have 600X600 dimensions while the images from India have 720X720 dimensions. And this dataset is created in different lighting and weather conditions.

Data download link : https://github.com/sekilab/RoadDamageDetector

## Plateform:
Google Colab

## Models
- SSD Mobilenet v1
- YOLO v3
