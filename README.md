# Hackthons
GA hackthons
The collecton of Project done for Hackthons at GreyAtom Edutech Mumbai


Hackthon 3 : Sentiment Analysis Hackathon

WittyWicky Inc. is a consulting firm that designs brand strategy for a lot of product startups. Their modus operandi is to gain the pulse of competing products and the associated sentiment from social media. Social media has profound impact in capturing the potential customers and thus there are a lot of consulting firms that operate in the digital strategy space. Whether it is to design a marketing campaign or look at the effect of marketing campaigns on user engagement or sentiment, it is a very valuable tool.
Manual assessment of sentiment is very time consuming and automatic sentiment analysis would deliver a lot of value. As a team of data scientists consulting for WittyWicky Inc., you are now responsible for meeting their business outcomes
Problem Statement
Twitter has now become a useful way to build one's business as it helps in giving the brand a voice and a personality. The platform is also a quick, easy and inexpensive way to gain valuable insight from the desired audience. Identifying the sentiments about the product/brand can help the business take better actions.

You have with you evaluated tweets about multiple brands. The evaluators(random audience) were asked if the tweet expressed positive, negative, or no emotion towards a product/brand and labelled accordingly.

Dataset Description
This dataset contains around 7k tweet text with the sentiment label.

The file train.csv has 3 columns

tweet_id - Unique id for tweets. tweet - Tweet about the brand/product sentiment - 0: Negative, 1: Neutral, 2: Positive, 3: Can't Tell

Evaluation Metric
We will be using ‘weighted’ F1-measure as the evaluation metric for this competition. For more information on the F1-metric refer to https://scikit-learn.org/stable/modules/generated/sklearn.metrics.f1_score.html






Hackthon 2:  Stayze Rent Predcition

overview:

Understanding the user behaviour has become a very crucial part for business nowadays. This understanding can help gain a lot of insights to customize a product according to user behaviour and make major business decisions. The problem you are about to solve is to predict the price of a rental property.

Problem Statement :

Stayze is an online market for providing lodging or primary homestays. The company does not own any real estate or properties, it acts as a broker receiving commission from each booking. The hosts rent out their property, its availability, area, type of room, price etc. and the travellers can book accordingly. The travellers put in their reviews, which is visible to others. People have used this service extensively and the company is recognized throughout the globe. All the online activities of the hosts as well as the travellers are being captured and have resulted in a rich database.

This data can be used to gain business insights, make decisions, improve security, understand the customers' and providers' (hosts) behaviour and performance on the platform, guiding marketing initiatives, implementation of innovative additional services and much more.

The stakeholders with the help of the available data want to know the ideal prices at which the properties can be rented, as it will help them decide upon the ideal investment to be done.

Can we build a machine learning model to predict the ideal price of the rental ?

Datasets :
The data folder data.zip that is provided to you contains the following files:

Train.csv - It is the training data containing the features, along with the price of the rentals.
Data_Dictionary.xlsx - It contains a brief description of every variable provided in the training and test set.
Test.csv: - It contains details of the customers for which the participants need to predict the price of the rentals.
sample_submission.csv - This is a sample file of the format in which you have to submit your predictions on GLabs.
Evaluation:
A solution with low root-mean-squared error (RMSE) based on cross-validation that can be reproduced and interpreted is ideal.
