# Machine Learning Mechanics – Terminology and Techniques

## 1. Target
> 1. What do I want to predict
> 2. What is the machine Learning Task

## 2. Objective
> 1. How would I evaluate success
> 2. What loss should I use?

## 3. Data
> 1. What data do I have
> 2. Data representation
> 3. Training/Test split
>> How to Look at the Data
>>> 3.1. How much data do you have? (N = ?)
>>> 
>>> 3.2. What are the Features?
>>>> - How many dimensions? (D = ?)
>>>> - What is the distribution
>>>> - Are they all numeric? => if not, there should be some transformation
>>>> - Are there missing values? => fillna or drop the row
>>>> 
>>> 3.3. What are the labels (are there labels)?
>>>> - Are they discrete? => this is one of the features that makes a dicision for loss function
>>>> - What is the distribution?
>>>> - Are there missing labels or errors? => fillna or drop the row
>>
>> ***Look at the data!! (sample, read, plot...)***

## 4. Example
> We are launching a new fashion trading website where people
can upload pictures of clothing they want to trade.
> - We want to automatically tag the clothing into categories based
on what sellers upload.
> - We have some example clothing pictures with category labels.
>> 1. What do we want to predict? => Type of clothing
>> 2. What data do we have? => Labeled Pairs
>> 3. How would we evaluate success? => Overall Accuracy?

## 5. Demo for visualization
> There is a demo for visualizing visual data (ex. photo) - [Link](https://colab.research.google.com/github/BerkeleyML/fa25-student/blob/main/lec/lec03/lec03.ipynb?authuser=1#scrollTo=Mtq3dxa3nMRq)

## 6. Taxonomy of Machine Learning
> Labeled Data
>> Supervised Learning
>> 1. Quantitative Label
>>>
>>> Regression
>> 2. Categorical Label
>>>
>>> Classification
>>>
> Reward
>>
>> Reinforcement Learning
>>
> Unlabeled Data
>> Unsupervised Learning
>>> Dimensionality Reduction
>>> 
>>> Clustering

### 6.1. Supervised Learning
> The “training data” consists of ***examples of a functional relationship.***
>> - Most commonly-used learning process
>> - The fastest way to learn – requires ***the least data.***
>> - Requires examples of the relationship

#### 6.1.1. Classification Problems
> 1. The **labels** are ***discrete class*** or ***categories***
> 2. Discrete labels are often ***encoded*** as ***numbers*** (but should be treated as classes)
> 3. Two main types of classification
>> - Binary Classification
>> - Multi-class Classification

## 7. Generalization

> Generalization is the ability of a model to perform well on new, unseen data sampled from the same distribution as its training data

### 7.1. Evaluating generalization through train-test split

> The train-test split is the standard technique we used to evaluate generalization in machine learning
>> 1. Shuffle the training data
>> 2. Split into 2 parts:
>>> - Larger Training Parts (~ 80%) - training and validation set
>>> - smaller Testing Parts (~ 20%)

## 8. Feature Engineering
> Feature engineering is the process of ***selecting*** and ***encoding*** the input feature from the raw features.
>> - Selecting Features : including the right features can help improve model performance.
>> - Encoding Features : Some features may need to be transformed into the appropriate numeric values.

### 8.1. Encoding Numerical Data
> Numerical features (numbers) are often used without modification. However, there are a few important exceptions:
>> - Categorical Features : 






 
