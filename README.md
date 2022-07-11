# Airbnb_Guest_Sentiment_Analysis.
Airbnb_Guest_Sentiment_Analysis
# Seattle_Airbnb_Open_Data_NLP_Guest_Comment_Analysis


![image.png](attachment:b70b1819-6678-4453-9333-0ad3de25e1cb.png)
#  Lets take a look what are they

# Business Understanding
* This project's purpose is how to acquire new clients and how to determine an optimum price to offer our services to clients for income maximization.

# Brief description
* Here Airbnb  Seattle open dataset is going to be investigated for the price adjustment and for understanding of which features effects the accommodation prices.
* Here we have 3 datasets and these datasets will be analysed seperately and also together to extract some valuable information.

* Question 1 Here I am going to observe room prices regarding to date
* Question 2 Effects of features on price.
* Question 3 Finally we are going to investigate  guest comments and prices and try to predict price of accommodation regarding to the guest comments.

 this dataframe shows  prices-dates-listing_id and availability
 so that we can may be extract some information of the seasonality of the prices 
/kaggle/input/seattle/calendar.csv


 Ok lets go to the next dataframe listings.csv here we will check correlation of price with some unexpected accommodation features.
/kaggle/input/seattle/listings.csv


 And finnally I am going to my a sentiment analysis with this that you can check the codes and comments are detaily explains the steps.
/kaggle/input/seattle/reviews.csv



 Prediction results can be discussed from different dimensions and model can be improved by combining review scores.
 Here I want to share my ideas about model predictions; price scales and guest comments can have an alignment however comments are regarding to the people's income levels and expectation 
 so that to deduce this can lead us to make mistake. From the otherside this can be used as a price adjustment tool for hosts. If the guests comments point you out as a high-luxirious 
 price scale accommodation why  would you set your price as a moderate price scale accommodation. Actually here in this case Cheap price scale accommodation comment accuracy is the lowest category
 this can show us some of these class accommodations are really cheaper than expected.
