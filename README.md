The goal of this project is to import data from an online source and process the data using various python libraries. You will design and implement a program that allows the user to enter a ticker symbol and perform a regression analysis of that asset against the S&P 500 to determine if there is any correlation. Submit the final project as a single Jupyter notebook file (.ipynb).
Collecting Data
Allow the user to enter a ticker symbol. Verify there is data available to import from Nasdaq Data Link or Alpha Vantage (You may need to instruct the user on how the symbol should be input so the appropriate data is returned)
Import daily prices (closing or adj closing). Use 1/1/2017 as the start date and 12/31/2017 as the end date. Display the first 5 rows and the total count for each asset.
Import daily prices for the S&P 500. Use 1/1/2017 as the start date and 12/31/2017 as the end date. Display the first 5 rows and the total count of the S&P.
Processing Data
Calculate daily % change (closing or adj closing) for the asset and the S&P 500. Display the first 5 rows and the total count for each data set.
Plot the daily % change (closing or adj closing) data using a bar graph for the asset.
Calculate and display the mean, standard deviation, variance, min, and max for the asset and the S&P 500.
Regression Analysis
Using scikit-learn, perform a linear regressions for the asset against the S&P 500. Y should be % change S&P 500. X should be % change for each asset.
For the regression, plot the samples and the linear model. Label the Y axis as S&P 500 and the X axis as each asset.
Calculate and display the intercept, coefficient (slope), R2, and the Mean squared error.
Indicate if the asset is positively or negatively correlated with the S&P 500
