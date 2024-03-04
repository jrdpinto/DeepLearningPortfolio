# Deep Learning Portfolio
A small collection of ANN models built while completing a [Udemy course on deep learning](https://www.udemy.com/course/deeplearning/learn/lecture/35733680#overview). Please note, these models are still a work in progress!

## Models

### Identifying Cats/Dogs in Images (Convolutional Neural Network)
![image](https://github.com/jrdpinto/DeepLearningPortfolio/assets/1144830/125d8c10-965f-4241-a03a-932f57d6a460)

A simple CNN built using data from a course on Udemy called [Deep Learning A-Z](https://www.udemy.com/course/deeplearning/learn/lecture/20260978). The dataset consists of several images of dogs and cats, split into training
and testing subsets.
NOTE: The accuracy and architecture of this model is a work-in-progress :)

### Stock Price Prediction (Long Short-Term Memory)
A stacked LSTM (Long Short-Term Memory) model built using data from a course on Udemy called [Deep Learning A-Z](https://www.udemy.com/course/deeplearning/learn/lecture/8374794). The dataset consists of Google's daily stock
price over 5 years from 03/01/2012 to 31/12/2016. The model attempts to predict a daily price for the stock, given 60 days of prior stock prices.
![image](https://github.com/jrdpinto/DeepLearningPortfolio/assets/1144830/025dd269-43b0-4e9a-8a0b-fd1c1595e27b)

### Fraud Detection (Self Organising Map)
![image](https://github.com/jrdpinto/DeepLearningPortfolio/assets/1144830/5dd127e0-1c47-4f99-9ec2-2b807edd7078)

A SOM model built using data from a course on Udemy called [Deep Learning A-Z](https://www.udemy.com/course/deeplearning/learn/lecture/6744454#overview). The model uses the Statlog (Australian Credit Approval) dataset obtained
from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/143/statlog+australian+credit+approval) which contains a list of credit card applications that were approved and rejected.
The aim of this model is to build a clustered map of credit card applications based on features in the dataset. The outliers in this map may help to identify the traits of fraudulent applications.

### Recommender (Restricted Boltzmann Machine)
A recommender system for movies, built using a Restricted Boltzmann Machine (RBM) that is trained on the [MovieLens](https://grouplens.org/datasets/movielens/) dataset. This model was built as part of a workshop for a Udemy
course called [Deep Learning A-Z](https://www.udemy.com/course/deeplearning/learn/lecture/6895718). 

### Churn Modelling (Classification Model)
A simple ANN built using data from a course on Udemy called [Deep Learning A-Z](https://www.udemy.com/course/deeplearning/learn/lecture/20258078#overview). The dataset lists customers at a bank who have either stayed with the
bank or chosen to leave, along with several data points for each customer such as their bank balance, credit score and geographic location. The aim of this model is to predict whether a given customer will stay or leave the bank,
based on the aforementioned data points.

### Hourly Electrical Output of a Power Plant (Linear Regression Model)
A simple ANN regression model built using the ['Combined Cycle Power Plant'](https://archive.ics.uci.edu/dataset/294/combined+cycle+power+plant) dataset from the UC Irvine Machine Learning Repository, and as part of a [Udemy course](https://www.udemy.com/course/linear-regression-with-artificial-neural-network/learn/lecture/18888982#overview) on building a regression model with an ANN. The dataset consists of 9568 data points collected from a Combined Cycle Power Plant. Features are as follows.
- Temperature (T) in the range 1.81°C and 37.11°C,
- Ambient Pressure (AP) in the range 992.89-1033.30 milibar,
- Relative Humidity (RH) in the range 25.56% to 100.16%
- Exhaust Vacuum (V) in the range 25.36-81.56 cm Hg
- Net hourly electrical energy output (EP) 420.26-495.76 MW

This model attempts to predict hourly electrical output given the Temperature, Ambient Pressure, Relative Humidity and Exhaust Vacuum.
