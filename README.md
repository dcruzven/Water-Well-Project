# Water-Well-Project

# Business Understanding 

We have been hired by the Tanzanian government to help them create a model that can accurately predict if a water well is functioning or in need of repair. In the data frame we analyzed there were over 55,000 water wells with over 50 features describing each individual water well. We narrowed down some of the data so that there would be less noise in our models. We made six different predictive models and then chose our best model to make our predictions. 

# Data Understanding 

We got our dataset from drivendata.org which had over 50,000 different water wells. We got rid of the variables that we thought would not have an impact on predicting the functionality of water wells. Our main objective for our model was to minimize false positives, which is when our model predicts that a water well is functional but it actually is in need of maintenance. To process all of this information, we decided to go with an XG Boost model because it had the least amount of false positives compared to the other models. We prioritized increasing our precision score to reduce false positives. 

# Results 

Our XG Boost model posted a precision score of 0.86 on the train data and .84 on the test data. Our accuracy score was .74 on the train data and .72 on the test data. Our final f1 score was .73 on the train data and .72 on the test data. Although our model does not excel in other metrics, it does an excellent job of reducing false positives while still being an effective model. 

# Future Analysis 

