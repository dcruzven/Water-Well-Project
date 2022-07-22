# Water-Well-Project

# Business Understanding 

We have been hired by the Humanitarian Relief Co. to help them create a model that can accurately predict if a water well is functioning or in need of repair.  In the data frame we analyzed there were over 55,000 water wells with over 50 features describing each individual water well. We narrowed down some of the data so that there would be less noise in our models. The features we focused on involved geographic location, population around the water well, and the year it was constructed. We made six different predictive models and then chose our best model, an XG Boost model, to make our predictions. Our goal is to reduce the amount of technicians sent to fix wells.

# Data Understanding 

We got our dataset from Taarifa and Tanzanian Ministry of Water. which had over 50,000 different water wells. We got rid of the variables that we thought would not have an impact on predicting the functionality of water wells. Our main objective for our model was to minimize false positives, which is when our model predicts that a water well is functional but it actually is in need of maintenance. To process all of this information, we decided to go with an XG Boost model because it had the least amount of false positives compared to the other models. We prioritized increasing our precision score to reduce false positives. We adjusted our thresholds to increase our precision while keeping the other scores at a reasonable value. 

# Results 

Our XG Boost model posted a precision score of 0.88 on the train data and .85 on the test data. Our accuracy score was .76 on the train data and .73 on the test data. Our final f1 score was .75 on the train data and .71 on the test data. Although our model does not excel in other metrics, it does an excellent job of reducing false positives while still being an effective model. 

# Future Analysis 

If we had more time, we would work to make our model more accurate and also decrease the amount of false negatives. We want to make sure that the Humanitarian Relief Co. has a reliable model that will not miss any water wells and only report water wells that need maintenance. 
