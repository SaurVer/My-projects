# BOARD GAME REVIEW PREDICTION

This is collection of my projects.
Project- Board Game Review Prediction
In this project, I have used the games data to predict the ratings/reviews given by the users. The project involves supervised learning with two regression models-1. Linear Regression, 2. Random Forest Regression. The whole process goes as follows -
1) Importing the basic packages like pandas, numpy, matplotlib, sklearn etc.
2) Loading and preprocessing of the data after analysing and visualizing the data. It involves removing all the data points where there was no user review and hence would impact our model negatively. Also, the redundant columns such as the id, type, name etc were removed.
3.) Splitting the data in test and train using sklearn. model_selection package
4) The LinearRegressor was initialised using sklearn.linear model and Random Forest Regressor from sklearn.ensemble.
5) These models were trained over our train data using appropriate tuning and tested on the test data.
6) The predictions were made on the test input to get the test output. The result was measured in terms of mean_squared_error imported from sklearn metrics.
7) The Random Forest Regressor performed better than the Linear Regressor.

# CREDIT CARD FRAUD DETECTION- Unsupervised Learning.

1)imported the required packages. Checked using the describe function if there is any null value.
2) Data is a PCA dimensionality reduced.
3) Since the data is huge, I have taken just the 10% of it to train the model.
4) Visualized the data using the histogram in each category as well as obtained the heatmap to see if two features have high correlation. One of the highly corelated features can be removed  as it is redundant and do not provide extra information.
5) Extracted the relevant data for  unsupervised learning
6) Trained the model(Local Outlier Factor and Isolation Forest) on this train data. And proceeded towards testing. 
7) Accuracy score and classification_report was generated to see the performance.
# Stock Market clustering with KMeans, PCA.
Unsupervised Learning
This project was very challenging for me. It has improved my skills in both ML and Python. Here I have imported stock prices of different international stocks from yahoo and tried to cluster them in groups using KMeans clustering. Few highlights are-
1) Learnt how to set up a pipepline in sklearn
2) Applied the PCA dimensionality reduction to check if results improve
3) Used normalizer function to normalize different stocks which can have a different scale of prices. If not standardized, the clustering will consider stocks with the same scale as one group. this will undermine other features.

The whole p[rocess goes as follows-
1) Data Loading- Made a dictionary consisting of 28 stocks with their tickers as their values
3) Imported the tock related information from yahoo using pandas_datareader data package.
4) Overviewed the data to find out that the data is multi-index.  Rows as dates while columns as stock's name under the stock feature such as 'High, 'Low', 'Close', 'Open' etc.
5) Basis of clustering was chosen to be the day-wise movement of individual stock prices
6) Movement array was oobtained using numpy.
7) The movement was visualised with matplotlib. It was found that the stock needs to be standardised.
Setting up of the sklearn Pipieline.
8) the pipeline consists of two elements namely: Normalizer()  and other the KMeans clustering.
9) The results were obtained. After this PCA dimensionality reduction was used to reduce the different dates features into just two.
10) KMeans was trained similarly and compared.
11) Finally, the results were visualized using a complex set of codes.
