# Analysis-of-Amazon-Fine-Food-Reviews
Predict review polarity by performing analysis on Amazon Fine Food Reviews dataset while applying various machine learning algorithms.

## Data
The data has been taken from https://www.kaggle.com/snap/amazon-fine-food-reviews.

## Data Overview

### Context
This dataset consists of reviews of fine foods from amazon. The data span a period of more than 10 years, including all ~500,000 reviews up to October 2012. Reviews include product and user information, ratings, and a plain text review. It also includes reviews from all other Amazon categories.

### Contents
Reviews.csv: Pulled from the corresponding SQLite table named Reviews in database.sqlite
database.sqlite: Contains the table 'Reviews'

### Data includes:
- Reviews from Oct 1999 - Oct 2012
- 568,454 reviews
- 256,059 users
- 74,258 products
- 260 users with > 50 reviews

### Columns
- IdRow: Id
- ProductId : Unique identifier for the product
- UserId : Unqiue identifier for the user
- ProfileName : Profile name of the user
- HelpfulnessNumerator : Number of users who found the review helpful
- HelpfulnessDenominator : Number of users who indicated whether they found the review helpful or not
- Score : Rating between 1 and 5
- Time : Timestamp for the review
- Summary : Brief summary of the review
- Text : Text of the review

## Data Cleaning and preperation
The data cleaning and preperation has been done only once which can be refered in <a href="https://github.com/NIkhileshOV/Analysis-of-Amazon-Fine-Food-Reviews/tree/master/T-SNE%20for%20Amazon%20food%20reviews"> T-SNE for Amazon food reviews </a>. This data is stored and used in all the other models directly.

# Acknowledgements
<a href="https://www.appliedaicourse.com/">AppliedAICourse</a>
