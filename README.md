<!-- hide -->
# Alternative Time Series Project Tutorial
<!-- endhide -->

- This project will let you practice your new skills on dealing with time series forecasting, by creating a cpu usage anomaly detection model.

## 🌱  How to start this project

You will not be forking this time, please take some time to read this instructions:

1. Create a new repository based on [machine learning project](https://github.com/4GeeksAcademy/machine-learning-python-template/generate) by [clicking here](https://github.com/4GeeksAcademy/machine-learning-python-template).
2. Open the recently created repostiroy on Gitpod by using the [Gitpod button extension](https://www.gitpod.io/docs/browser-extension/).
3. Once Gitpod VSCode has finished opening you start your project following the Instructions below.

## 🚛 How to deliver this project

Once you are finished creating your anomaly detection model, make sure to commit your changes, push to your repository and go to 4Geeks.com to upload the repository link.

## 📝 Instructions

**Anomaly detection on CPU usage**

Anomaly Detection means to identify unexpected events in a process. It means to detect threats to our systems that may cause harm in terms of security and leakage of important information, but the importance of Anomaly Detection is not limited to security. The data of this project is based on per-minute metrics of the host’s CPU utilization.

Dataset links:

cpu-train-a: https://raw.githubusercontent.com/oreilly-mlsec/book-resources/master/chapter3/datasets/cpu-utilization/cpu-train-a.csv

cpu-train-b: https://raw.githubusercontent.com/oreilly-mlsec/book-resources/master/chapter3/datasets/cpu-utilization/cpu-train-b.csv

cpu-test-a: https://raw.githubusercontent.com/oreilly-mlsec/book-resources/master/chapter3/datasets/cpu-utilization/cpu-test-a.csv

cpu-test-b: https://raw.githubusercontent.com/oreilly-mlsec/book-resources/master/chapter3/datasets/cpu-utilization/cpu-test-b.csv

**Step 1:**

In Machine Learning ARIMA model is generally a class of statistical models that give outputs which are linearly dependent on their previous values in the combination of stochastic factors.

We need to visualize the data to analyse the trends, seasonalities, and cycles.

We'll start by importing necessary libraries.

**Step 2:**

Load the datasets.

**Step 3:**

Using matplotlib visualize the data.

**Step 4:**

Use the ARIMA model to fit the data.

**Step 5:**

Evaluate the performance

**Step 6:**

Run the actual prediction by using the most recent 100 observed data points followed by the 60 predicted points.

**Step 7:**

Let’s perform the same anomaly detection on another segment of the CPU utilization dataset captured at a different time by using the cpu-train-b

Can you visualize any anomaly that occurs a short time after the training period?

**Step 8:**

Put your conclusions in the README file as a summary. And don't forget to create this model in your app.py file.