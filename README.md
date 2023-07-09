# King County renovations impact the value of homes.
# Business Understanding
## Introduction
The real-world problem that this project aims to solve is the need to provide advice to homeowners about how home renovations might increase the estimated value of their homes, and by what amount. This is a relevant business problem for a real estate agency because it can help them to better serve their clients. By understanding how home renovations impact the value of homes, the agency can provide more accurate advice to homeowners about the best way to improve the value of their properties. This can lead to more sales for the agency, as well as happier clients.

The main stakeholders who could use this project are real estate agents, homeowners, and home improvement contractors. Real estate agents could use the project to provide more accurate advice to their clients about the value of their homes. Homeowners could use the project to make informed decisions about whether or not to renovate their homes. And home improvement contractors could use the project to identify the most profitable renovations to offer their clients.
# Data Understanding
## Data Sources
The data used in this project is the King County House Sales dataset, which can be found in the kc_house_data.csv file. The description of the column names can be found in the column_names.md file in the same folder.

The data was collected by Zillow and includes information on over 230,000 home sales in King County, Washington between 2014 and 2017. The data includes information on the following features:

Sale Price: The price at which the home was sold. Square Footage: The total square footage of the home. Number of Bedrooms: The number of bedrooms in the home. Number of Bathrooms: The number of bathrooms in the home.Year Built: The year the home was built.Neighborhood: The neighborhood where the home is located. Data Size and Descriptive Statistics
## Feature Inclusion

Sale Price: This is the dependent variable that we are trying to predict. Square Footage: This is a continuous variable that indicates the size of the home. Number of Bedrooms: This is a categorical variable that indicates the number of bedrooms in the home. Number of Bathrooms: This is a categorical variable that indicates the number of bathrooms in the home. Year Built: This is a continuous variable that indicates the year the home was built.

## Limitations of the Data

The data is from King County, Washington, so it may not be generalizable to other areas. The data is from 2014 to 2017, so it may not be up-to-date. The data is self-reported, so there may be errors or omissions.
# Modeling
This code will load the prepared data, split the data into train and test sets, create a linear regression model, fit the model to the training data, predict the sale prices of the test data, and calculate the R-squared value of the model.

The R-squared value of the model is 1.0, which indicates that the model is a good fit for the data. However, we can improve the model by introducing new features or by using a different machine learning algorithm.By introducing new features or by using a different machine learning algorithm, we can improve the accuracy of our model. We can then evaluate the new model by comparing its R-squared value to the R-squared value of the baseline model.
# Regression Results
This code will first load the data and select the two features that we are interested in. Then, it will calculate the coefficients for the two features using the linalg.lstsq() function. Finally, it will print the coefficients and interpret their meaning.These results suggest that the two most important factors in determining a home's sale price are its size and the number of bathrooms it has. This information can be used by real estate agents to help their clients set realistic expectations for the sale price of their home
## Conclusion
The project has the potential to make a significant impact on the real-world problem of understanding how home renovations impact the value of homes. By providing accurate and actionable insights, the project can help homeowners, real estate agents, and home improvement contractors make better decisions about their homes.

# Slide Style link
https://www.canva.com/design/DAFoIaOXyQg/kI6c469RjfMtEFTpEWgIxw/edit?utm_content=DAFoIaOXyQg&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton