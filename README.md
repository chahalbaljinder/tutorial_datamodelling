**DATA CLEANING:**

Data cleaning is a crucial step in the process of preparing data for modeling. When it comes to data modeling, data cleaning involves various aspects to ensure the data is accurate, consistent, and reliable for modeling purposes. Some of the key aspects of data cleaning in the context of data modeling include:
Handling missing values: Data cleaning involves identifying and addressing missing values in the dataset. Depending on the nature of the missing values, techniques like imputation (replacing missing values with a calculated estimate) or deletion of records with missing values may be used.

**Removing duplicates**: Duplicates in the dataset can skew modeling results, so part of data cleaning involves identifying and removing duplicate records to ensure the data is unique.

**Standardizing data**: Data cleaning involves standardizing different representations of the same data. For example, converting categorical variables into a consistent format or ensuring consistency in date formats.

**Handling outliers**: Outliers can significantly impact model performance, so data cleaning often involves detecting and dealing with outliers through techniques like trimming, winsorization, or transformation.

**Dealing with inconsistencies**: Data cleaning also involves identifying and rectifying inconsistencies in the data, such as typos, formatting errors, or conflicting values across different columns.

**Feature engineering**: Data cleaning can also include feature engineering, where new features are created from existing ones to improve model performance. This might involve binning, scaling, or transforming variables.

**Normalization and scaling**: Ensuring that the data is on a similar scale is crucial for many models. This involves normalizing or scaling features to a consistent range.

**Clean the data by:**

->removing rows that have values which are missing

->changing the data type of some values within a column

->removing columns which are not relevant to this task.


**DATA MODELLING:**

Data modeling is the process of creating a conceptual representation of the data structures and relationships within a given domain. It is a crucial step in the design and implementation of databases, data warehouses, and information systems. The goal is to ensure data consistency, integrity, and to facilitate the efficient retrieval and manipulation of data.

Now we have to figure out the top 5 categories from the atteched files. 

To complete your data modelling, follow these steps:

**1. Create a final data set by merging your three tables together**

We merge three tables using the Reaction table as your base table, then first join the relevant columns from your Content data set, and then the Reaction Types data set.

For merge above mentioned tables using "VLOOKUP" formula/function.
 
**2. Figure out the Top 5 performing categories**

Add up the total scores for each category.

we'll use the “Sum If” formula

**3. The end result we create one spreadsheet which contains:**

A cleaned dataset

The top 5 categories


