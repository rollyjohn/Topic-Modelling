# How Topic Modelling can help companies to mine through comments and reviews?


People love to leave feedbacks about the products and services in multiple channels like social media platforms, product websites, merchant websites etc. Companies have to constantly monitor user rating and comments to protect themselves. At the same time smart companies leverages these comments as sources for improvement. 
While I was trying to work on the  comments people leave from app store I wanted to see what more I can apply to user comments apart from sentimental analysis. Can I quickly sort through the comments and find out the topics people are appreciating, or dissatisfied with? Can I send only the relevant comments to relevant teams? 

## Topic Modelling

Topic modelling is one tools of Natural Language Processing(NLP) that helps someone to go through huge textual documents and quickly find out what the document is talking about.  The document is broken down into corpus state first and then the topic model algorithm set out to finding the probabilities of occurrence of particular words in particular topics. For example "dog" and "bone" will appear more frequency in a document about dogs. The document may also be talking about cats, but we can assume that in a document about dogs there would probably 9 times more dog words than cat words. Topic modelling help to capture this. 
How I applied topic modelling to appstore reviews

## Background

All banks provide their customers banking experience through the Mobile apps. For the new gen banking customers a smooth mobile banking experience is a must have. For this project I am going to use the Apple app store reviews left for the net banking mobile app of a leading Indian bank. I extracted 1000 reviews using 'app_store_scraper' package and filtered for reviews with less than 4 rating, i.e negative reviews, for analysis. 


References:

•	Blei, David M.; Ng, Andrew Y.; Jordan, Michael I; Lafferty, John (January 2003). "Latent Dirichlet allocation". Journal of Machine Learning Research.

•	https://www.machinelearningplus.com/nlp/topic-modeling-gensim-python/ 

•	https://www.analyticsvidhya.com/blog/2016/08/beginners-guide-to-topic-modeling-in-python/ 


