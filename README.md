# NYC-Taxi-Trip-Analysis-and-Predictions
Explore New York Taxi Trip records in 2015, making visualizations, predict trip duration (ETA) and fare.

# Dataset
- [NYC Yellow Taxi 2015 sample data](https://www.kaggle.com/edwinytleung/nyc-yellow-taxi-2015-sample-data)
- I created the dataset and uploaded them in Kaggle. The dataset is based on the 2015 NYC Yellow Cab trip record data published by the NYC Taxi and Limousine Commission (TLC). The train data was randomly sampled which is 2% of the whole year dataset. The test data is non overlapping with the train data and is 1% of the whole year dataset.

**File descriptions**

- train.csv - the training set (contains 2874263 trip records) 

- test.csv - the testing set (contains 1446517 trip records)

**Update:**

I have uploaded the train and test dataset with geodesic distance calculated by library geopy (from the coordinates in the dataset) to save up the time for calculation. [Notebook for using the geopy library](https://github.com/edwinytleung/NYC-Taxi-Trip-Analysis-and-Predictions/blob/master/Calculate%20distance%20using%20Geopy%20function.ipynb)

- Weather 2015.csv - Daily weather features, e.g. temperature, rainfall, snowfall, etc. [csv link](https://github.com/edwinytleung/NYC-Taxi-Trip-Analysis-and-Predictions/blob/master/Weather%202015.csv)

**Showing anomalies**
- [Notebook link](https://github.com/edwinytleung/NYC-Taxi-Trip-Analysis-and-Predictions/blob/master/Anomalies.ipynb)

**Main Notebook**
- [Notebook link](https://github.com/edwinytleung/NYC-Taxi-Trip-Analysis-and-Predictions/blob/master/Taxi.ipynb)

# Pre-trained models

- kmeans_clf.pkl - kmeans classifier
- lightgbm_rgr.pkl - lightgbm trip duration regressor
- lightgbm_fare_rgr.pkl - lightgbm fare regressor
- keras_taxi.h5 - deep learning model for trip duration prediction
