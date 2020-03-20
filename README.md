# Machine Learning Model to Predicting Used Cars Prices

[Cristian Baldi](https://www.linkedin.com/in/crisbal/) - [Fabrizio Olivadese](https://www.linkedin.com/in/fabrizio-olivadese-71a445b3/) - Simone Vitali

University Of Milano Bicocca - Department of Computer Sciences, Systems and Communications

## Abstract
The aim of this paper is to propose a machine learning model to predict the sale price of used cars. To train and validate the model a dataset obtained from scraping Ebay is used, consisting of user-submitted listings of various car models in various conditions. A crucial part of the problem was dealing with large amount of missing values, false and placeholder listings and overall outlier detection. After cleaning the dataset various machine learning models are compared to ﬁgure out the best one for the task. An ensemble-like model is also developed which proved a small improvement in overall performance. The performance of both solutions are then evaluated, resulting in good results, especially considering the training data in use, but with room for improvements.
## Introduction
Used car sales accounts of about 33% of all the car sales inEurope and the used-car market share is expected to rise inthe next years by 7% in terms of value for each year [Tech-navio 2017].

Buying and selling new cars is easier thandealing  with  used  ones:  manufacturers  provide  pricingsheets to the final customer that tell how much a certaincar with a certain configuration will cost.Dealing  with  the  used  market  instead,  it  is  much  morecomplex: an inexperienced driver, looking to purchase itsfirst vehicle, might find very difficult to tell if the price hehas to pay for an used car is too high or right for the statusof the car.  At the same time, someone looking to sell anused car might be interested in knowing how much it canbe sold for,  without spending days in researching otherlistings for the same model and conditions. In the used-car market, kilometers, age, general conditionof the car, but also the maker and the model of the car, areall things to keep in mind when trying to estimate howmuch a car is worth. 
It is clear how anautomated tool topredict the value of a carstarting from some of its details,could be very useful for the car market as a whole.The aim of this work is to build such a tool using machine-learning techniques, mainly implementingregression mod-els for the priceof a certain car. First of all, different models that can be applied directlyto the car characteristics to predict the price are compared,then it is shown an ensemble-like model that predicts theprice by first trying to categorize the car in a general price-range direction (cheap, medium, expensive) and later usinga specific machine learning model for the predicted price-range.

To train  and  validate  the  various  models  adataset  con-sisting of around 370,000 uses-submitted listingsto EbayGermany is used. The dataset contains a lot of dirty, miss-ing and malformed data, consisting of typos, fake listingsand wrong user-submitted data in some attributes of thecar details.

The  proposed  problem  is  not  an  easy  task  to  complete,firstly because second-hand prices still depends a lot on theseller feelings and estimations on what its car is worth (onemight even put a price without comparing it to the otherprices on the market) and secondly because the dataset inuse for this problem, even after a preprocessing phase, stillcontains malformed data that could alter the predictions.



[Read here the final report](https://github.com/Fabrolly/Machine-Learning-Model-to-Predicting-Used-Cars-Prices/blob/master/Final%20Report.pdf)

