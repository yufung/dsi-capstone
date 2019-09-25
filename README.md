# Capstone: Hawker Food AI

Image classifier for Singapore hawker food pictures.

## Problem Statement

Singapore has nominated its Hawker Culture for the UNESCO’s Representative List of Intangible Cultural Heritage of Humanity in March 2019. Documentation is key to safeguarding our Intangible Cultural Heritage, and everyone is welcomed to make [online photo contributions](https://www.oursgheritage.sg/ourhawkerculture-online-photo-contributions/) to document Singapore’s hawker centres and food. Although most photos are tagged by their contributor, the traditional workflow of image labeling is tedious and inefficient. To make future photo archiving efforts on Singapore's food heritage easier and faster, the aim of this project is building an image classifier that can label Singapore hawker food pictures. To make the project manageable, I will be classifying 10 categories of food and 1 non-food category.

[Link to presentation slides](https://docs.google.com/presentation/d/1H2IDRye7ZxFESfMldawTqsCMVw040iGScZTaWIG8HK4/edit?usp=sharing) \| [Link to web app demo](http://hawkerai.tamyufung.com) \| [Link to Telegram bot](https://telegram.me/hawkerfood_bot)

## Data 

Our dataset contains 16500 images grouped in 11 equal classes - 10 food classes and 1 non-food class. 80% of the dataset was used for training and 20% was used for validation.

Food images were scraped from Instagram using [igScrape](https://github.com/yufung/igscrape). Images from posts with a given hashtag, such as #chickenrice, were downloaded.

Non-food images were taken from the [Food-5K dataset](https://mmspg.epfl.ch/downloads/food-image-datasets/) by the Ecole Polytechnique Fédérale de Lausanne.

The total size of our dataset is about 1.26 GB.

### Classes

- Bak Chor Mee
- Bak Kut Teh
- Char Kway Teow
- Chicken Rice
- Fried Hokkien Mee
- Laksa
- Nasi Lemak
- Non Food
- Roti Prata
- Satay
- Wanton Mee
