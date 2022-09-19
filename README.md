 # DATA-SCIENCE-PROJECT

# A LOGISTIC REGRESSION MODEL ON WHAT PRODUCT KENYAN RETAILERS SHOULD STOCK IN AN INFLATIONARY MARKET.

# Problem statement.

With high inflationary environment and high cost of goods,  consumers are facing pressure on what retail goods to prioritize over. This makes it even harder for retailers who are also budgeting for what goods to stock up on to prevent massive losses and to hopefully ride out the harsh economic times.


# Objectives.


 * To find relevant data for the study.
 * To identify features necessary for this model
 * To create  the model
 * To test this data on a test dataset

# Aim.

The aim of this project is to create a model for small or large scale retailers to use, so as to identify what products to stock up on based on the products qualities and consumer behavior as the features, and an aggregate score as a target.

# DATA
The data used in the study was generated from mockaroo all with values ranging from 0 to 1 so as to indicate the quantitative value of the features used in probability form.

# Features
Features used in the data include: 'Brand Loyalty',	'Purchase Frequency',	'Profit margin',	'Quality',	'sale opportunities',	'resale value',  'after sale service', 	'competition',  'Tax rate', 	'score'. All being factors that affect the products perfomance in the market and also reflect consumer behaviour.
Products that contain these features include:
 Convenience products
 Shopping products
 Specialty products
 Unsought products


The 'score' column is an aggregate of all the features and subtracting features that are undesirable or would be costly for a retailer eg. 'after sale service', 	'competition',  'Tax rate'. 


 # Logistic Regression Assumptions

 

* The independent variables should be independent of each other. That is, the model should have little or no multicollinearity. 
* Binary logistic regression requires the dependent variable to be binary.
* For a binary regression, the factor level 1 of the dependent variable should represent the desired outcome.
* Only the meaningful variables should be included.
* The independent variables are linearly related to the log odds.


