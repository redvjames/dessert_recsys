# dessert_recsys
A Project for Data Mining and Wrangling 2 Course of Asian Institute of Management's Master of Science in Data Science 2023 

If you're a foodie, you know the struggle of deciding what to cook for your next meal. With thousands of recipes available online, it can be overwhelming to choose just one. That's where a personalized recommendation system comes in handy. And that's precisely what this project aims to achieve for dessert lovers on food.com!

The pandemic has led to a surge in home cooking, and food.com has become a go-to destination for many recipe seekers. However, the platform lacks a recommendation system to help users navigate through the vast collection of recipes available. This project addresses that gap by creating a recommender system based on user preferences.

Using a Kaggle dataset of scraped recipes and user interactions from food.com, the team implemented a comprehensive data science pipeline to generate personalized recommendations for clustered users and items. The dataset was pre-processed to remove duplicates and filter out unnecessary data, and dimensionality reduction techniques were applied to manage computational efficiency and memory constraints. The team used clustering techniques to identify user and item clusters, and various collaborative filtering methods were used to generate recommendations based on user ratings.

The study found that the most effective was the latent-factor-based collaborative filtering technique which provided personalized recommendations with high coverage, balanced novelty score, and high intra-list similarity score. This means that users can get recommendations that are tailored to their preferences while still exploring new options. The study also recommends further improvements by applying other clustering techniques and algorithms, content-based collaborative filtering, and exploring other food categories.

With this project, food.com users can enjoy a personalized recommendation system that improves their experience and engagement on the platform. Whether you're a dessert enthusiast or a curious recipe seeker, this recommender system will help you find your next favorite dessert recipe in no time!

Original Data Source: This dataset consists of 180K+ recipes and 700K+ recipe reviews covering 18 years of user interactions and uploads on Food.com (formerly GeniusKitchen). It was used in the following paper:

Generating Personalized Recipes from Historical User Preferences
Bodhisattwa Prasad Majumder, Shuyang Li, Jianmo Ni, Julian McAuley
EMNLP, 2019
https://www.aclweb.org/anthology/D19-1613/

The dataset can be downloaded from Kaggle: https://www.kaggle.com/datasets/shuyangli94/food-com-recipes-and-user-interactions
