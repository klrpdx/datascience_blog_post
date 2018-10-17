# Data Science Blog Post


   
### Overview
   
The goal of this project is to gather, clean, and analyze a data set and
then use that data with models and visualizations to answer business questions. The
end result fo this work is a general-audience blog post explaining the findings.


For this project, I used a data set from Kaggle containing wine descriptions, prices,
scores, and other details for over 130,000 wines: https://www.kaggle.com/zynicide/wine-reviews

I hope to answer 3 questions regarding the language used to describe wines:

1. Does the language vary with the variety of the wine? Based on the reviewer's description,
could you make a good guess at the type of wine?

2. How does the language vary with the price of wines?

3. How does language vay with the score awarded to wines? Does it match the language
for prices?

My overall motivation is to improve my ability to describe wine by analyzing the words
used my experts.


### Results

There is a clear difference in language used when describing different varieties of
wine. Berries are used in the description of red wines, while citrus flavors are 
commonly used for different varieties of white wines. Also, the language varies within
the varieties of red and white.

Language differs with the price of wine as well. High priced wines are more likely to
be described as lush, complex, or dark. Lower priced wines are described as simple, light,
and clean.

High-priced wines tend to be high scored as well, and the language tends to be the same.
Low scoring wines, though, are described in harsh terms that distinguish them from
inexpensive wine. 


### Libraries Used
-  pandas
-  sklearn stop words
-  sklearn TfidVectorizer
-  sklearn CountVectorizer
-  nltk word_tokenize
-  python collections Counter
-  matplotlib
-  numpy
-  WordCloud


### Required Files
-  winemag-data-130k-v2.csv: CSV file containing 130K wines and their reviews.
-  wine_stop.txt: List of words commonly found in wine reviews that are not significant 
for describing the wine.



