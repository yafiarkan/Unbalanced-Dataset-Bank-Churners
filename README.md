# Background

A manager at the bank is disturbed with more and more customers leaving their credit card services. They would really appreciate if there is a system that can predict customer who use other bank services for them, so the manager can proactively go to the customer to provide them better services and turn customers' decisions in the opposite direction.

I got this dataset from a website with the URL as https://leaps.analyttica.com/home. I have been using this for a while to get datasets and accordingly work on them to produce fruitful results. The site explains how to solve a particular business problem.

Now, this dataset consists of 10,000 customers mentioning their age, salary, marital_status, credit card limit, credit card category, etc. There are nearly 18 features. We have only 16.07% of customers who have churned. Thus, it's a bit difficult to train our model to predict churning customers.

# Methodology

To overcome the unbalanced amount of data, this project compares the oversampling and undersampling methods. In order to keep the performance measurement on-track, this project uses the ROC curve to measure the performance of a model whose dataset is imbalanced. ROC curve that is close to 1 means that the model built has good performance with an optimal cutoff value and avoids high variance/overfitting.

# Result

Oversampling produces a better ROC curve of 0.94 and has an accuracy of 92% on the neural network. So this result is considered to be able to distinguish which customers switch bank services/use two or more bank services, and which customers continue to use bank services
