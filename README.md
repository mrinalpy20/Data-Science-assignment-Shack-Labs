# Data-Science-assignment-Shack-Labs
Shack Labs Internship project
This project has 2 problem statements:
No 1: The goal is to understand the relationship between house features and how these variables affect the house price. Using more than one model, predict the price of the house using the given dataset. Please compare the accuracy of the models along with the drawbacks of each technique's assumptions before recommending the final prediction model.

Solution:
The given dataset is reviewed and some features were selected for performing data analysis and predictions.
Visualistion techniques like plotting of graphs and data structures like dictionaries were employed to get a better understanding of data.
3 features namely 'House size (sqft)','Distance from nearest Metro station (km)','House Age' were selected to perform predictions.
Four machine learing models namely Random forest,Multiple regression, BayesianRidge and ElasticNet were used and Random forest came out as the best fit.

No 2:Using ML/DL techniques, match similar products from the Flipkart dataset with the Amazon dataset. Once similar products are matched, display the retail price from FK and AMZ side by side. Please explore as many techniques as possible before choosing the final technique. You may either display the final result in single table format OR You may create a simple form where we input the product name and the output of prices of the product from both websites are displayed.
Solution:
First of all we perform feature selection and found out that the features of product name and pid were the most relevent ones. 
Product names however had some annomalies in them (like the quantity wasn't considered and were written in an irregular upper and lower case) so we choose pid as the best feature. 
After selection of feature we modified the dataframe according to our need and displayed the product in a tabular form.
