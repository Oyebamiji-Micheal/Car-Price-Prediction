<h1>Car Price Prediction</h1>
<h4>A Beginner's Approach to Machine Learning</h4>

<img src="images/cover.jpg">

<p align="justify">In this repository, we are going to be solving a simple machine learning problem together which involves predicting the prices of cars based on features such as engine size, fuel system, bore ratio, etc.  The purpose of this repository is to introduce newbies to what a typical machine learning workflow looks like. This repository is not a tutorial on "what pandas is" or "how to get started with numpy". Readers are assumed to be familiar with the basics of pandas and related libraries.</p>

<h3>Download Dataset</h3>
<p align="justify">The first step is obtaining a dataset. There are numerous websites with open source datasets such as Kaggle, Github, UCI and so on. The dataset used in this repository is sourced from Kaggle, a website which hosts data science competitions and open source data. The link to the dataset can be found <a href="https://www.kaggle.com/datasets/hellbuoy/car-price-prediction">here</a>.</p>

<h3>Data Exploration</h3>
<p align="justify">Understanding the dataset we are working with is crucial in machine learning. Some of the common data exploration steps are included below</p>

- <strong>Checking the first five rows of the dataset</strong>:  This is the first step in getting a glimpse of what our dataset looks like and the type of data present in each column. This step is particularly important so we do not work blindly.

- <strong>Data Size</strong>: Knowing the size of the dataset is important for a lot of reasons. For example, the size of our dataset influences the type of algorithm we choose.

- <strong>Statistical Properties</strong>: The next step in our data exploration is to check some statistical properties of the dataset such as mean, standard deviation and percentiles. These properties help us understand the distribution of our data along with some potential outliers. For example, the standard deviation of car prices is 7989 while the median is 10295. This suggests that there are some cars that are highly expensive with their price differing significantly from the rest.
 
- The last step is to check the information about each column. This is usually done using the info() function from pandas.

<h3>Exploratory Data Analysis</h3>
<p align="justify">The best way to truly understand a dataset is to visualize it. Most data scientists skip this step as they see it as boring or not so important. However, this step is very important in order to know the kind of preprocessing to be done such as outlier removal, data clipping, log transformation, etc.</p>

The rest of the tutorial can be followed up on <a href="https://medium.com/@oyebamijimicheal10/car-price-prediction-a-beginners-approach-to-machine-learning-9584a117a60d">medium.</a>