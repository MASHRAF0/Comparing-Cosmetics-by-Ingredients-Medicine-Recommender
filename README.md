# Comparing Cosmetics by Ingredients Medicine Recommender
## Description

Whenever I want to try a new cosmetic item, it's so difficult to choose. It's actually more than difficult. It's sometimes scary because new items that I've never tried end up giving me skin trouble. We know the information we need is on the back of each product, but it's really hard to interpret those ingredient lists unless you're a chemist. You may be able to relate to this situation.

![Chemicals](https://www.3eco.com/sites/default/files/styles/blog_full/public/Thumbnails/blog-laboratory-technicians-lab-chemicals-dark.jpg?itok=Rl_S0kLx)

So instead of buying and hoping for the best, why don't we use data science to help us predict which products may be good fits for us? In this notebook, we are going to create a content-based recommendation system where the 'content' will be the chemical components of cosmetics. Specifically, we will process ingredient lists for 1472 cosmetics on Sephora via word embedding, then visualize ingredient similarity using a machine learning method called t-SNE and an interactive visualization library called Bokeh. Let's inspect our data first.

## Libraries & Packages

![numpy](https://img.shields.io/badge/Numpy-%25100-blue)
![pandas](https://img.shields.io/badge/Pandas-%25100-brightgreen)
![Matplotlib](https://img.shields.io/badge/Matplotlib-100-informational)
![ScikitLearn](https://img.shields.io/badge/ScikitLearn-%25100-red)
![bokeh](https://img.shields.io/badge/bokeh-100-important)

## Dataset

🏆 To begin with, let's load the metadata about the data. This Data set contains, product names, Ingredients, skin preference,This Data set contains, product names, Ingredients, skin preference and price.
Data available via kaggle: https://www.kaggle.com/datasets/kingabzpro/cosmetics-datasets

.


## Project Steps 

* We are going to create a content-based recommendation system where the 'content' will be the chemical components of cosmetics. Specifically, we will process ingredient lists for 1472 cosmetics on Sephora via word embedding, then visualize ingredient similarity using a machine learning method called t-SNE and an interactive visualization library called Bokeh. Let's inspect our data first.
