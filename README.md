# CRISP-DM-BANK
Goal is to compare the performance of the classifiers encountered, namely K Nearest Neighbor, Logistic Regression, Decision Trees, and Support Vector Machines. A dataset related to marketing bank products over the telephone will be used.. 

# Campaign
The dataset comes from the UC Irvine Machine Learning Repository Links to an external site.. The data is from a Portuguese banking institution and is a collection of the results of multiple marketing campaigns. Vast number of marketing campaigns over time has reduced its effect on the general public. Furthermore, economical pressures and competition has led marketing managers to invest on directed campaigns with a strict and rigorous selection of contacts.
The dataset collected is related to 17 campaigns that occurred between May 2008 and November 2010, corresponding to a total of 79354 contacts.
There are two main approaches for enterprises to promote products and/or services: through mass campaigns, targeting general indiscriminate public or directed marketing.
## Dataset Information
### Additional Information

The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed. 

There are four datasets: 
1) bank-additional-full.csv with all examples (41188) and 20 inputs, ordered by date (from May 2008 to November 2010), very close to the data analyzed in [Moro et al., 2014]
2) bank-additional.csv with 10% of the examples (4119), randomly selected from 1), and 20 inputs.
3) bank-full.csv with all examples and 17 inputs, ordered by date (older version of this dataset with less inputs). 
4) bank.csv with 10% of the examples and 17 inputs, randomly selected from 3 (older version of this dataset with less inputs). 
The smallest datasets are provided to test more computationally demanding machine learning algorithms (e.g., SVM). 

The classification goal is to predict if the client will subscribe (yes/no) a term deposit (variable y).
### Baseline Model - using small dataset from Bank_addditional.csv 
[Text(0.4, 0.875, 'x[10] <= 0.082\ngini = 0.194\nsamples = 3295\nvalue = [2936, 359]'),
 Text(0.2, 0.625, 'gini = 0.0\nsamples = 2935\nvalue = [2935, 0]'),
 Text(0.30000000000000004, 0.75, 'True  '),
 Text(0.6, 0.625, 'x[10] <= 0.332\ngini = 0.006\nsamples = 360\nvalue = [1, 359]'),
 Text(0.5, 0.75, '  False'),
 Text(0.4, 0.375, 'x[8] <= 0.082\ngini = 0.5\nsamples = 2\nvalue = [1, 1]'),
 Text(0.2, 0.125, 'gini = 0.0\nsamples = 1\nvalue = [0, 1]'),
 Text(0.6, 0.125, 'gini = 0.0\nsamples = 1\nvalue = [1, 0]'),
 Text(0.8, 0.375, 'gini = 0.0\nsamples = 358\nvalue = [0, 358]')]
<img width="785" height="790" alt="image" src="images/Bank_Addition_base Model.png" />
