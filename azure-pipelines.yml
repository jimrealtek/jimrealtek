#import modules
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
%matplotlib inline
sns.set(color_codes=True)

#Load the carpricedetection.csv dataset
carprice = pd.read_csv('carpricedetection.csv')

#display all the columns and 5 rows record from the top
heading = carprice.head(2)
print(heading)

print('\n')

#Display the datatype used in all the columns
datatype = carprice.shape
print(datatype)

print('\n')

#Load dataset from the bottom
tail = carprice.tail(2)
print(tail)

print('\n')

#Display all the columns in the dataset
column = carprice.columns
print(column)

print('\n')

#Analytical summary of the dataset
summary = carprice.describe(include='all')
print(summary)

print('\n')

#Histogram plotting on each column
Histogram = carprice.hist(figsize=(25,30))
print(Histogram)

