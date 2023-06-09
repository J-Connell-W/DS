# Exploratory Data Analysis

As it stands now I am interested in learning Data Science as it is used in machine learning.
</br>
The steps below are only applicable after a data set has been gathered. Once there is a new data set we must "clean" the data set and make sure that it is in a usable state. This means we must remove columns if they are irrelevant, address outliers, handle missing values, and check for errors that may have been caused when entering the data. 
<br/>
Another step is to start to find out where relationships between variables may exist. 
<br/><br/>
The goal is to have the possibly messy and unrefined data set come to you; clean it by fixing the aforementioned problems, then output a data set that is useful for a model.
<br/><br/>

### Some definitions provided by gpt-4 I am curious if they are accurate. 

<br/>
<br/>
<h3> Data cleaning: </h3> 
<br/>

Handle missing values, remove duplicates, and correct inconsistencies in the data. This ensures that the model learns from accurate and consistent information.

<br/>
<br/>

### Feature engineering: 

</br>
Create new features or transform existing ones to better represent the underlying patterns in the data. This can help the model capture the relationships more effectively.
</br></br>
For my understanding I will add that it can include the acts of combining certain variables into one, and it is just overall manipulating the data into a usable form.

<br/><br/>
### Feature selection: 
</br>
Identify the most relevant features for the task at hand, which can help improve model performance, reduce overfitting, and speed up training.

<br/><br/>
### Scaling and normalization: 
</br>
Standardize the features so that they have similar scales and ranges, which can help some models converge faster and perform better.

<br/><br/>
### Encoding categorical variables: 
</br>
Convert categorical variables into numerical representations (e.g., one-hot encoding) that can be fed into the model.

<br/><br/>
### Handling imbalanced data sets: 
</br>
If the target variable has imbalanced classes, you might need to resample the data or use appropriate evaluation metrics to ensure that the model doesn't become biased towards the majority class.



## Some steps to start

It seems that we want to be able to see different ways that the data is structured using some commands such as the pandas dataframe.describe method this allows us to see some statistics about the data such as its:

### Count

This is the number or non null or non-NA observations in the data for that feature

<br/>

### Mean

The mean of the values for that feature. This can be used to see what potential outliers are in the data.

<br/>

### Standard Deviation

The standard deviation, which measures the dispersion or spread of the non-missing values in each feature. This can help to show how far apart the values are from eachother in a particular category. Can be used to determine how to scale the data.

<br/>

### Min

The minimum value for the feature that is not NA. Helpful for seeing the range of the data.

<br/>

### 25%

The first quartile (25th percentile), which is the value below which 25% of the non-missing values in each feature fall.

<br/>

### 50%

The median (second quartile or 50th percentile), which is the value that separates the lower 50% from the upper 50% of the non-missing values in each feature.

<br/>

### 75%

The third quartile (75th percentile), which is the value below which 75% of the non-missing values in each feature fall.

<br/>

### 100%

The maximum value of the non-missing values in each feature.

<br/>

## Correlation Matrix

Another useful 
