# Natural Language Processing Project for E-Commerce Users Reviews and Ratings

In this NLP project we will be attempt to classify Women's E-Commerce Clothing Reviews into 1 star or 5 star categories based off the text content in the reviews. We will utilize the pipeline methods with Multinomial Naive Bayes. The complete EDA and modeling can be found in the notebook [here](https://github.com/javadfarshchi/Natural-Language-Processing-E-Commerce-Review/blob/main/NLP_Project_E_Commerce.ipynb)).

Each observation in this dataset is a review of a particular product by a particular user.

We will use the Women's E-Commerce Clothing Reviews Data Set from Kaggle with 23,000 reviews and ratings (found [here](https://www.kaggle.com/datasets/nicapotato/womens-ecommerce-clothing-reviews)).

The "ratings" column is the number of stars (1 through 5) assigned by the reviewer to the product. (Higher rating is better.) In other words, it is the rating of the product by the person who wrote the review.

## Dataset Content
This dataset includes 23486 rows and 10 feature variables. Each row corresponds to a customer review, and includes the variables:

* Clothing ID: Integer Categorical variable that refers to the specific piece being reviewed.
* Age: Positive Integer variable of the reviewers age.
* Title: String variable for the title of the review.
* Review Text: String variable for the review body.
* Rating: Positive Ordinal Integer variable for the product score granted by the customer from 1 Worst, to 5 Best.
* Recommended IND: Binary variable stating where the customer recommends the product where 1 is recommended, 0 is not recommended.
* Positive Feedback Count: Positive Integer documenting the number of other customers who found this review positive.
* Division Name: Categorical name of the product high level division.
* Department Name: Categorical name of the product department name.
* Class Name: Categorical name of the product class name.

![Dataset Head](https://github.com/javadfarshchi/Natural-Language-Processing-E-Commerce-Review/blob/main/Dataset_Head.PNG)

## Prediciton and Evaluation of Multinomial Naive Bayes Model
The result of our prediction model and the evaluation can be found in the picture below. We can observe that the model has predicted the reviews categories with **high precision.**

![Dataset Head](https://github.com/javadfarshchi/Natural-Language-Processing-E-Commerce-Review/blob/main/Prediction_Evaluation.PNG)

