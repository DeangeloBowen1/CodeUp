# DS Notes for CodeUp
# Open Discussion 2nd Day
23 March 2022 - Open Discussion

Supervised vs.　Unsupervised learning:
- Supervised Data runs on data w/answers/labels/etc
- Unsupervised learning doesn’t have any answers about data. 


Supervised learning algorithms:
- Regression (ordinary least squares)
- Classification (Decisions trees, or “questions in data”, random forests, KNN or logistic regression)
- Time series (forecasting)

Unsupervised learning algorithms:
- Clustering algorithms
- K-means clustering (focusing on datapoints that have low distance between them)
- DBScan (density based clustering)
- Dimensionality reduction (Ex. If you have width and length as 2 features in your dataset, what if using area is helpful? We then went from 2 dimensions to 1, because a = L * W)

Structured data vs Unstructured:
- structured data = tables, sheets, rectangles (rows + columns)
- Unstructured data = text, audio, video, pictures

Continuous numeric data vs discrete numeric data vs categorical:
Discrete numeric data :
- is 1,2,3 whole numbers like # of bedrooms and bathrooms, 2.5 baths etc. Sometimes order matters with discrete like 1st 2nd 3rd and other ordinal numbers. Sometimes order of the numbers doesn’t matter like phone numbers. 

Continuous numeric variables : 
- Values with tons of precision or possibility like:
- Temperature
- Age in nanoseconds
- Weight
- Prices

Categorical variables are categories: 
- True/false
- Red/green/blue

Regression vs. Time series:
-Time series is a variable explained with time (Yesterday, day, time, etc)(What was the weather like 10 days ago and how does that effect today) Time series data is dependent on another area based in time.

-Regression is non-time based analysis so like, what was the weather based off of barometric pressure or someones opinion on a matter.  Regression is independent data. 

# Data Science Pipeline Information

Data Science Pipeline

Planning Phase : 

- Clearly define the scope of the project by making sure the people who are going to receive the final project have exactly what they need in the project. 

- Succeed in the project by visualizing a proper end-point for the people who matter.

- How to get there? Collaborate with the people who need it by asking questions on things like operation.

- Also, using a workflow process too for workflow management once again by making sure you can visual everything you are and will be working on. 

- Make sure to stay true to the data against all adversaries but do so respectfully, still proudly. 

The Goal:

- Create a path from original data sources to the environment that you work in. 

How to get there:

- By getting the data from a cloud to SQL
- Perhaps from HTML scraping to data
- Compiling JSON packages
- Spreadsheet parser
- Turn it all into a .py file

Preparation :

AKA Data Cleaning, Tidying, and wrangling (acquisition + prep)

The goal : 

- Putting data into random samples in a format that can easily be explored analyzed and visualized. 

How to get there : 

- Find out what is making the data messy
- Find outliers and anomalies 
- Finding incorrect data types
- Turing them into a model (.py)
- Clean data and creature new features
- Split into train, validate, and test phases
- Convert into proper measurements (ms to s for example)
- Scale the data

Exploration: 

The goal : 
- Discover features that have the latest impact on the target variable
- Provide the most information gain
- Drive the outcome

How to get there:

- Hypotheses testing 
- Data Visualization 
- Engineering features techniques to improve performance in the model without losing data. 


Modeling:

The goal: 
- Create a robust and generalizable model that is mapping between features and a target outcome 

How to get there : 
- Start with data in a training set (that came from the previous data)
- Take the training set and push it to build multiple models (regression model, decision tree model)
- Now test the models against a validation set of your training data

Delivery : 

The goal : 

- Enable others to use what you have learned or developed through all the previous stages. 

How to get there : 

- Presentation or report
- Notebook or scripts that can be ran on someone else’s computer
- Dashboards and endpoint 

