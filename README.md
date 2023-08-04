<!-- hide -->
# Time series
<!-- endhide -->

- Understanding a new dataset.
- Analyze the time series and study its characteristics.
- Train a model to predict future memory expenditure.

## 🌱  How to start this project

You will not be forking this time, please take some time to read these instructions:

1. Create a new repository based on [machine learning project](https://github.com/4GeeksAcademy/machine-learning-python-template/generate) by [clicking here](https://github.com/4GeeksAcademy/machine-learning-python-template).
2. Open the newly created repository in Codespace using the [Codespace button extension](https://docs.github.com/en/codespaces/developing-in-codespaces/creating-a-codespace-for-a-repository#creating-a-codespace-for-a-repository).
3. Once the Codespace VSCode has finished opening, start your project by following the instructions below.

## 🚛 How to deliver this project

Once you are finished creating your linear regression model, make sure to commit your changes, push to your repository and go to 4Geeks.com to upload the repository link.

## 📝 Instructions

### System for detecting CPU usage anomalies

We want to train a system that is able to predict what may be the CPU computational expenditure of a computer based on its historical data. To do this, we have captured some data for every minute several days to try to train a model.

#### Step 1: Loading the dataset

The dataset is already divided into training and test and can be found in this project folder under the names `cpu-train.csv` and `cpu-test.csv`. You can load them in the code directly from the links (`https://raw.githubusercontent.com/4GeeksAcademy/alternative-time-series-project/main/cpu-train.csv` and `https://raw.githubusercontent.com/4GeeksAcademy/alternative-time-series-project/main/cpu-test.csv`) or download it and add it by hand to your repository.

#### Step 2: Construct and analyze the time serie

Construct the valid data structure for the time serie, graph it, and then analyze it and answer the following questions:

- Which is the tensor of the time serie?
- Which is the trend?
- Is it stationary?
- Is there variability or noise?

> NOTE: A `tensor` in a time serie is the minimum unit of time for which there is data. It can be every second, minute, hour, day, week, month...

#### Step 3: Train an ARIMA

Use the training data to find the best parameterization of your ARIMA model.

#### Step 4: Predict with the test set

Now use the trained model with the test set and compare the points with the real ones. Measure the performance of the time serie.

#### Step 5: Save the model

Store the model in the corresponding folder.