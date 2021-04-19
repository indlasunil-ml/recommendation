Heroku URL: https://my-recommendation-system.herokuapp.com/

Important File Summary:

app.py : Contains API Definitions 
model.py : Contains API Implementations to get top 5 recommended products
Sentiment_Based_Product_Recommendation_System.ipynb : Entire code of sentiment analysis models and recommentation system 
sample30.csv : User Product Review Datatset used while model building and Recommendation system.
sample30_processed.csv: User prodcut review dataset with extra processed text columns used in model.py to speed up the text process step
user_final_rating_cos.csv: used for recommending top 20 products 
tfid.pkl: used for converting review text as tokens
randomforest.pkl: used in model.py for predicting sentiment of top 20 products from reco engine to sort it to top 5 positive rated products.