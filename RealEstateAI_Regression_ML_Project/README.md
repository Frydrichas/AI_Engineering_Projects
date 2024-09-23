# A prediction model for the real estate market

RealEstateAI Solutions aims to optimize real estate price valuation through the use of advanced regularization techniques in linear regression models. The goal is to provide more accurate and reliable price predictions, reducing the risk of overfitting and improving the model's generalization ability.

In the real estate sector, obtaining accurate property price estimates is crucial for making informed decisions. However, traditional linear regression models can suffer from overfitting, compromising prediction accuracy. It is necessary to explore effective regularization methods to improve predictive performance and manage model complexity.

By implementing and comparing regularization methods such as Lasso, Ridge, and Elastic Net, RealEstateAI Solutions will offer a system capable of providing more accurate and stable real estate price predictions. This will allow real estate agents and investors to make decisions based on more reliable data, increasing their competitiveness in the market.

**Project Requirements:**

1. **Dataset Preparation:**
* Loading and preprocessing real estate price data.
* Handling missing values, encoding categorical variables, and normalizing/scaling data.

2. **Model Implementation:**
* Ridge Regression: Implementation and training of the model with Ridge regularization.
* Lasso Regression: Implementation and training of the model with Lasso regularization.
* Elastic Net Regression: Implementation and training of the model with Elastic Net regularization.

3. **Performance Evaluation:**
* Use of cross-validation techniques.
* Calculation of Mean Squared Error (MSE) for each model.
* Comparison of model complexity by evaluating the number of non-zero coefficients.
* Analysis and comparison of results from the various regularization methods.

4. **Results Visualization:**
* Creation of charts to visualize and compare model performances.
* Visualization of residual distribution to assess model adequacy.
* Visualization of the trend of model coefficients concerning regularization parameters.

The project must include the complete source code, with detailed comments explaining the various steps, choices made, and results obtained, to ensure transparency and replicability of the work.

# The dataset

The dataset is available here: https://proai-datasets.s3.eu-west-3.amazonaws.com/housing.csv (freely adapted from the following dataset: https://www.kaggle.com/datasets/yasserh/housing-prices-dataset)

* Price: the price, the target to predict
* Area: the property's surface area
* Bedrooms: the number of bedrooms
* Bathrooms: the number of bathrooms
* Stories: the number of floors
* Mainroad: 1 if the property faces a main road, 0 otherwise
* guestroom: 1 if the property has a guest room, 0 otherwise
* basement: 1 if the property has a basement, 0 otherwise
* hotwaterheating: 1 if the property has a boiler, 0 otherwise
* airconditioning: 1 if the property has air conditioning, 0 otherwise
* parking: the number of parking spaces
* prefarea: 1 if the property is in a prestigious area, 0 otherwise
* Furnishingstatus: 0 if the property is unfurnished, 1 if it is partially furnished, 2 if it is fully furnished