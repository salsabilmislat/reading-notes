# What we will learn

- Data Science Primer 

The source of this summary [The first link](https://elitedatascience.com/primer)

______________________________________

## Data Science Primer

![Data Science](https://elitedatascience.com/wp-content/uploads/2018/05/What-Goes-Into-a-Successful-Model.jpg)


## Bird's Eye View

### Machine learning

**Machine learning is the study of computer algorithms that can improve automatically through experience and by the use of data. It is seen as a part of artificial intelligence.But Machine learning is a comprehensive approach to solving problems. individual algorithms are only one piece of machine learning**

### Key Terminology

  * Model - a set of patterns learned from data.

  * Algorithm - a specific ML process used to train a model.

  * Training data - the dataset from which the algorithm learns the model.

  * Test data - a new dataset for reliably evaluating model performance.

  * Features - Variables (columns) in the dataset used to train the model.

  * Target variable - A specific variable you're trying to predict.

  * Observations - Data points (rows) in the dataset.


## Exploratory Analysis

**Which is just fancy-talk for “getting to know” your data.Doing so upfront will make the rest of the project much smoother,exploratory analysis for machine learning should be quick, efficient, and decisive, not long and drawn out**

* You’ll gain valuable hints for Data Cleaning (which can make or break your models).

* You’ll think of ideas for Feature Engineering (which can take your models from good to great).

* You’ll get a "feel" for the dataset, which will help you communicate results and deliver greater impact

**Plot Numerical Distributions**

*At this point, you should start making notes about potential fixes you'd like to make. If something looks out of place, such as a potential outlier in one of your features, now's a good time to ask the client/key stakeholder, or to dig a bit deeper.*


## Data Cleaning

*If you have a clean dataset, even simple algorithms can learn impressive insights from it. proper data cleaning can make or break your project. Professional data scientists usually spend a very large portion of their time on this step.*

**Handle Missing Data**
*you cannot simply ignore missing values in your dataset.*

the 2 most commonly recommended ways of dealing with missing data

    - Dropping observations that have missing values

    - Imputing the missing values based on other observations

## Feature Engineering

*Feature engineering is about creating new input features from your existing ones.You can isolate and highlight key information, which helps your algorithms "focus" on what’s important.You can bring in your own domain expertise.nce you understand the "vocabulary" of feature engineering, you can bring in other people’s domain expertise*

## Algorithm Selection

*In applied machine learning, individual algorithms should be swapped in and out depending on which performs best for the problem and the dataset. Therefore, we will focus on intuition and practical benefits over math and theory*

### Regularization in Machine Learning

**Regularization is a technique used to prevent overfitting by artificially penalizing model coefficients.It can discourage large coefficients (by dampening them).It can also remove features entirely (by setting their coefficients to 0), The "strength" of the penalty is tunable.**



### Model Training

**Split Dataset**

*If you evaluate your model on the same data you used to train it, your model could be very overfit and you wouldn’t even know! A model should be judged on its ability to predict new, unseen data.*




