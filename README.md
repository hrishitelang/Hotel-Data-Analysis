# Hotel-Data-Analysis
IST 687 Project

## Description
1. The Hotel Industry, in general, has always been volatile when it comes to reservation and cancellation of rooms. Some customers have reserved hotel rooms months, sometimes even a year before arrival. However, many of these customers potentially cancel bookings due to unforeseen reasons and other factors.
2. Several attributes cause this to happen. After analysis, we found several factors that when targeted can significantly reduce cancellations. Thus, as data scientists, on behalf of the hotel industry, we aim to understand the historical data and analyze hotel booking trends. These factors can be used to report the trends and predict future bookings.
3. With the various insights and analyses obtained, we aim to generate insights that can help drive business decisions on how to reduce cancellation bookings and essentially improve profits in the hotel business.


## Technical Details
1. There are 20 features and 40,060 observations available in the dataset.
2. The dataset is not overwritten, and columns are not renamed for ease of understanding and coding.
3. Upon checking the NULL and missing values, we found out that there are no missing values; however, the NULL values were present in the country column as string values, which we converted into actual null type variables.
4. We also identified the categorical values (by converting them into factor variables) and numerical data. We created separate datasets, one to perform association rules mining and another to perform ML classification.

## Goals/Objectives
The overall goal of the project is to provide actionable recommendations, based on the insights.

## Objective
1. To perform analysis on columns such as cancellation, customer type, market segment, among other attributes.
2. Implement various Machine Learning algorithms to predict cancellation.
3. To analyze why people cancel hotel reservations and predict who will be canceling
4. To analyze:
  a) The number of cancellations:
    i) Number of bookings on a weekday vs weekends
    ii) Most preferred meal types
    iii) Country-wise bookings
    iv) New customers acquired
    v) Type of rooms preferred by customers
    vi) Booking types
    vii) Assigned Rooms
    viii) The number of guests in each booking
    
  b) Analyze patterns associated with each segment, such as:
    i) Day of week
    ii) Type of customers
    iii) Type of rooms
    iv) Market Segment
    
   c) Predict future cancellations based on machine learning algorithms such as the Apriori algorithm, linear modeling, support vector machines, and classification and regression trees.
   d) Using these results, we can make critical business decisions regarding the customer experience they desire to deliver.
   
## Libraries Used
We used the following libraries for the project
Tidyverse, caret, rworldmap, skimr, ggplot2, arules, readr, rpart, e1071, rpart.plot
