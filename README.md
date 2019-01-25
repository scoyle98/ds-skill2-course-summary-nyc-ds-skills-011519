
# Overview of Course Objectives

We've covered a lot in this course, starting from the ground up with what python is, how to import packages, the basics of machine learning, and using enterprise database systems. Below is a general outline. As we wrap up the course, take some time to go through the outline below and review some of the many new skills that you are starting to become familiar with. This is a great time to ask some final questions, refresh your memory on old concepts and start to organize resources to help you as a budding data scientist going forward!  

1. Python basics
    1. Data types
        1. strings
            1. slicing
        2. ints
        3. floats
        4. lists
            1. append
            2. pop
            3. remove
        5. dictionaries
            1. dict.get(value, default) #useful for updating dictionary values
        6. tuples
        7. booleans
    2. Iteration: for, while, break
    3. Conditionals: if, elif, else
    4. Try / Except Clauses
    5. Functions
        1. def func_name(inputs):
            """docstring"""
            #stuff to do
            return blah
2. Python Packages
    1. PANDAS
        1. DataFrames
            1. df.head()
            2. df.set_index()
            3. df[df["col"]=="value"] #Filtering on a boolean
            4. df.sort_values(by="col_name", ascending=False) #sort by a column
        2. Series
            1. df["col"] #selecting a column
            2. df.col #alternative format
            3. df.col.value_counts()
            4. df.col.quantile(q=) #percentiles of a series
    2. Matplotlib
        1. import matplotlib.pyplot as plt
        2. %matplotlib inline
        3. plt.plot()
        4. plt.title()
        5. plt.xlabel() #and plt.ylabel()
        6. df.plot(kind='barh') #alternatively, kind='bar' or kind='scatter' etc.
        7. plt.figure(figsize=(10,10)) #change figure size
        8. plt.subplots()
3. Machine Learning:
    1. Supervised Learning
        1. Train - test splits
        2. Regression
            1. OLS
            2. Greedy Selection
                1. Observed how coefficients changed when adding features to our model
            2. Lasso/Ridge
                1. Normalizing against overfitting
            3. Adding Polynomial Features
            4. Measuring performance
                1. r^2
                2. train vs test error
                3. MSE
                4. MSLE
     

4. SQL
    1. Select statements
    2. Order by
    3. Limit
    4. Where
    5. Group by
    6. Having
    7. Joins
        1. Inner join
        2. Outer join
5. APIs
    1. HTTP Requests
        1. Headers
        2. OAuth
            1. Authentication Tokens
    2. JSON


