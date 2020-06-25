# Project-Analyze-A-B-Test-Results

# Problem statement:
To help the company understand if they should implement the new page, keep the old page, or perhaps run the experiment longer to make their decision.


 >>>>>>>>>>>>>>![pageAB](pageAB.gif) 
 
# Introduction

This repository contains  project work applying Practical inferential statistics and probability to important, real-world scenarios, in analyzing A/B tests and building supervised learning models.


A/B tests are very commonly performed by data analysts and data scientists. It is important that you get some practice working with the difficulties of these


For this project, I worked to understand the results of an A/B test run by an e-commerce website.The goal was to help the company understand if they should implement the new page, keep the old page, or perhaps run the experiment longer to make their decision.

#
[Dataset 1](https://github.com/abel-keya/Project-Analyze-A-B-Test-Results/blob/master/ab_data.csv):

The dataset has the following features:
 * user_id
 * timestamp
 * group
 * landing_page
 * converted

[Dataset 2](https://github.com/abel-keya/Project-Analyze-A-B-Test-Results/blob/master/countries.csv): 


The dataset contains the following columns;

* user_id	
* country

# Context

 A/B testing, or split testing, presents 50% of users with an alternate version of a webpage in order to test the effectiveness of a particular variable. A/B tests are evaluated based on whether the alternate page achieves a higher conversion rate. To ensure that results are not impacted by uneven sample sizes, it's important to evenly split both page versions among all visitors (hence the term "split testing").

AB Tests and Conversion Rates
Every page on an ecommerce website promotes a desired action to be taken by visitors, and A/B tests aim to increase the conversion rate of that action. Conversions include:

* Buying a product - the primary and most important conversion for an online store
* Subscribing to a service
* Signing up for a newsletter
* Submitting a survey response

# Description

The project work is divided into the following sections:


Introduction

Part I - Probability

Part II - A/B Test

Part III - Regression

### Findings/Results

### probabilities
The experiment was carried out on a population of 290584 users, 35237 converted. Probability of an individual converting regardless of the page they receive was 0.11959667567149027, the probability of an individual in the control group converting was 0.1203863045004612, probabilityan of an individual in the treatment group converted was 0.11880724790277405 Probability that an individual received the new page or old page was 50% for all the sample population. The convert rate for the new page was 11.96% whereby all the participants had an equal chance of 50% of getting either the old or new page.

### Regression analysis
The null and alternative hypotheses associated with your regression model

H0:β1=0

H1:β1≠0

p-values associated with all the variables were greater than 0.05 which is the recommended value, This differerd because the regression model performs a 2-sided Test, This was an indication that there is no relation between a user seeing either page(old/new) and the conversion .As a result the experiment has a Type I error and the Null hypothesis is rejected.

The test failed to reject the null hypothesis,The ecommerce company is therefore not adviced to change the page.There is no relation between then type of page and the conversion rate.

# Requirements

* Anaconda installation
* Google colab
* Setup instruction
> * Save a copy of the notebook in your drive and open it to access.

<p align="center">
   
   # Technologies used:
   
 <p align="center"> 
   
  <img   src="https://github.com/abel-keya/week8_IP_Abel_Keya_Nairobi-Hospital-conducted-a-clinical-camp-to-test-for-hypothyroidism/blob/master/tech3.jpg" width="550" height="300"  alt="DS" title="Requirements" />
 
</p>

# Support
In case of any clarifications or suggestions with regards to this project email me at jumakeya@gmail.com

License
Copyright (c) 2020 **Abel Keya**

