# Auto-Insurance
Auto insurance binary classification industry-grade project.

I Developed a machine learning model to predict whether an owner will initiate an auto insurance claim in the next year or not and hence identify good customers based on historic data.

## Background

The auto insurance industry is witnessing a paradigm shift. Since auto insurance company
consists of homogenous good thereby making it difficult to differentiate product A from
product B, also companies are fighting a price war (for insurance price). On top of that, the
distribution channel is shifting more from traditional insurance brokers to online purchases,
which means that the ability for companies to interact through human touchpoints is limited,
and customers should be quoted at a reasonable price. A good price quote is one that makes
the customer purchase the policy and helps the company to increase the profits.
Also, the insurance premium is calculated based on more than 50+ parameters, which means
that traditional business analytics-based algorithms are now limited in their ability to
differentiate among customers based on subtle parameters.

## Process Flow
The Machine Learning model mainly consist of two phases:

### 1. EDA (Exploratory Data Analysis):

Analyze the datasets to summarize their main characteristics (with visual methods). A statisticalmodel can be used, primarily EDA can be used to see what the data can tell us beyond the formal
modeling or hypothesis testing task.

Following tasks can be performed as a part of EDA:

o Scaling/Normalization

o Fill the missing values

o Feature selection & engineering

### 2. Machine Learning Modeling :

After EDA, the modeling comes into the process. The process of training an ML model involves providing an ML algorithm (that is, the learning algorithm) with training data.
The term “ML model” refers to the model artifact that is created by the training
process.
The training data must contain the correct answer (target or target attribute). The
learning algorithm finds patterns in the training data that maps the input data
attributes to the target (the answer that you want to predict), and it outputs an ML
model that captures these patterns.
You will use the ML model to get predictions on new data for which you will not know
the target.

Following tasks can be performed as a part of Modeling:

• Start with the basic model but eventually move towards ensemble

• Use Deep Learning with sklearn MLPClassifier and check if the Neural Network
Model is better than traditional models

• Arrival at a model with best f1-score

## Dataset Description

The project involves the use of a dataset with 600k training data and 57 features/data. 
In the train and test data, features that belong to similar groupings are tagged as such in the feature names (e.g., ind, reg, car, calc). In addition, feature names include the postfix bin to indicate binary features and cat to indicate categorical features. Features without these designations are either continuous or ordinal. Values of -1 indicate that the feature was missing from the observation. The target column signifies whether a claim was filed for that policy holder.
