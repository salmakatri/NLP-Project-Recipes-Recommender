# NLP-Project-Recipes-Recommender
## Design
Online websites such as Tasty, Recipes.com and Food.com make it very easy for a cook to research any dish by name to get full recipe with ingredients and instructions. This project aims at creating a Recipe Recommender based upon the content of the recipes previously consumed and rated by the user. This would provide users with personalized recommendations for new recipes to try, providing them with new options and saving time on research.  
## Data Description
I will use the Food.com scraped dataset available on Kaggle. The dataset consists of 180K+ recipes and 700K+ user reviews across 18 years of users interactions. The recipes dataset contains recipe name, ingredients, instructions, time and contributor id. The user reviews dataset contains user id, recipe id, rating and text review. 
## Tools
* Pandas for data manipulation
* Nltk, scipy, sklearn, gensim, corex, lightfm for modeling
* Matplotlib, Seaborn and Tableau for visualization
## Algorithms and Models
Started with text preprocessing:
* Text cleaning
* Lemmatization
* Compound Terms
* Speech tagging
* Removing stop words

Followed by topic modeling using different algorithms:
* LSA
* NMF
* LDA
* Corex (with and without anchors)

Finally, I expolred different recommendation algorithms
* Content-based
* Collaborative Filtering using users rating data
* Hybrid: LightFM

## Communication
All projects methodology and results are presented in the project slides. I am also working on creating a web app to display the recipe recommendation model. 
