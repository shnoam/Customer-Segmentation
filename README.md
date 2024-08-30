# Customer-Segmentation

## Overview

This mini-project involves customer segmentation using various clustering techniques.

The goal is to analyze customer data and group similar customers together based on their characteristics and behaviors.

It was developed as part of my preparation for an interview.

## About the data
  retreived from E-commerce Customer Behavior Dataset on kaggle.
  Columns:

  Customer ID:
  
  Type: Numeric
  Description: A unique identifier assigned to each customer, ensuring distinction across the dataset.
  Gender:
  
  Type: Categorical (Male, Female)
  Description: Specifies the gender of the customer, allowing for gender-based analytics.
  Age:
  
  Type: Numeric
  Description: Represents the age of the customer, enabling age-group-specific insights.
  City:
  
  Type: Categorical (City names)
  Description: Indicates the city of residence for each customer, providing geographic insights.
  Membership Type:
  
  Type: Categorical (Gold, Silver, Bronze)
  Description: Identifies the type of membership held by the customer, influencing perks and benefits.
  Total Spend:
  
  Type: Numeric
  Description: Records the total monetary expenditure by the customer on the e-commerce platform.
  Items Purchased:
  
  Type: Numeric
  Description: Quantifies the total number of items purchased by the customer.
  Average Rating:
  
  Type: Numeric (0 to 5, with decimals)
  Description: Represents the average rating given by the customer for purchased items, gauging satisfaction.
  Discount Applied:
  
  Type: Boolean (True, False)
  Description: Indicates whether a discount was applied to the customer's purchase, influencing buying behavior.
  Days Since Last Purchase:
  
  Type: Numeric
  Description: Reflects the number of days elapsed since the customer's most recent purchase, aiding in retention analysis.
  Satisfaction Level:
  
  Type: Categorical (Satisfied, Neutral, Unsatisfied)
  Description: Captures the overall satisfaction level of the customer, providing a subjective measure of their experience.
## In the code

- **Data Processing**: preprocess customer aggregated data.
- **Clustering**: Apply KMeans and DBSCAN clustering algorithms.
- **Visualization**: Visualize clusters and feature distributions using various plots.
- **Dimensionality Reduction**: Use PCA for visualization of high-dimensional data.

## Optional Future Work
  1.  Apply other tecniques to evaluate K-Means - for example, Siiluette score
  2.  Adjust DBSCAN parameters for better results
  3.  Explore more patterns in the data, apply seperate clustering on customer groups (e.g Gender, City, Membership type...)
