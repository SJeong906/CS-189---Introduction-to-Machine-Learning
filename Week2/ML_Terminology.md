# Machine Learning Mechanics – Terminology and Techniques

## 1. Target
> 1. What do I want to predict
> 2. What is the machine Learning Task

## 2. Objective
> 1. How would I evaluate success
> 2. What loss should I use?

## Example for 1 and 2
> We are launching a new fashion trading website where people
can upload pictures of clothing they want to trade.
> - We want to automatically tag the clothing into categories based
on what sellers upload.
> - We have some example clothing pictures with category labels.
>> 1. What do we want to predict? => Type of clothing
>> 2. What data do we have? => Labeled Pairs
>> 3. How would we evaluate success? => Overall Accuracy?

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

## 4. Demo for visualization
> There is a demo for visualizing visual data (ex. photo) - [Link](https://colab.research.google.com/github/BerkeleyML/fa25-student/blob/main/lec/lec03/lec03.ipynb?authuser=1#scrollTo=Mtq3dxa3nMRq)
 
