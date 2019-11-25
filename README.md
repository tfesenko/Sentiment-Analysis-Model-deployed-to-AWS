# Sentiment-Analysis-Model-deployed-to-AWS
Deploying a Sentiment Analysis Model Project is a part of Udacity Deep Learning Nanodegree.

The prediction model is implemented in PyTorch and deployed to AWS SageMaker.   
To serve it on a web page, I call the SageMaker model from a AWS Lambda service, which can be accessed via API Gateway.

## What is it?

It's a deployed web page which defines sentiment of a movie review.  

Below are results for some reviews for "[Au service de la France](https://www.imdb.com/title/tt4367560/reviews?ref_=tt_urv)":
---
![Positive review](https://github.com/tfesenko/Sentiment-Analysis-Model-deployed-to-AWS/blob/master/screenshots/PositiveReview2.png)
---
![Negative review](https://github.com/tfesenko/Sentiment-Analysis-Model-deployed-to-AWS/blob/master/screenshots/NegativeReview1.png)
