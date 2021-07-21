# Gu's Construction Pricing Model

### Author: Harrison Gu

## Overview

This project uses housing data in King County to build a linear regression model to predict the price of houses based on certain features about the house. The model will be used by Gu's Construction company to determine what types of houses they want to build.

### The Data

This project strictly used the King County House Sales dataset, and used to following features:

* bedrooms
* bathrooms
* sqft_living
* sqft_lot
* view
* waterfront
* zipcode
* basement
* sqft_living15
* sqft_lot15

### Analysis

To get the most accurate model, I made the following adjustments to the data:

* Remove outliers
* Log transform
* One hot encode categorical variables
* Min-max scale continuous variables
* Remove features with insignificant p-values
* Check for interactions between variables

### Conclusion

Zipcodes most highly correlated with price:

-98039 

-98004

-98112 

-98109

-98102 

Features most highly correlated with price:

-sqft_living 

-waterfront 

-sqft_living15 

Features with negative correlation with price:

-bedrooms 

-floors 

-basement 

### Next Steps

For further investigation, I will do cost benefit analysis for all the features. For example, homes in zipcode 98039 sell for the highest price, but buying land in that area could also be more expensive, thus reducing the net benefit of building a house there.
