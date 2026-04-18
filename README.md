# EXP16
Aim:
To apply NLP techniques on text data using Python.

Theory:
Natural Language Processing (NLP) is a field of Artificial Intelligence and computational linguistics that allows machines to understand, interpret, and generate human language. Text data—such as emails, social media posts, customer reviews, news articles, medical records, and legal documents—is one of the most widely available forms of unstructured data. Unlike structured datasets, raw text cannot be directly used in computational models and must first be transformed into a structured, numerical format.

Key operations and functions include:

pd.merge(df1, df2, on='Key'): Merges two DataFrames by matching rows based on a common column.
how='inner': Keeps only the rows where matching keys exist in both DataFrames.
how='outer': Retains all rows from both DataFrames, inserting NaN where matches are missing.
how='left': Keeps all rows from the left DataFrame and only matching rows from the right.
how='right': Keeps all rows from the right DataFrame and only matching rows from the left.
df.columns: Displays the column names in the DataFrame.
df.shape: Returns the size of the DataFrame in terms of rows and columns.
df.info(): Provides a summary including data types, non-null values, and memory usage.
df.describe(): Generates summary statistics such as mean, count, and standard deviation for numerical columns.
print(df): Displays the DataFrame for review.

Conclusion:
The study demonstrates that NLP techniques on text data can be effectively implemented in Python, enabling the transformation of unstructured text into structured formats suitable for analysis, using tools such as the NLTK library.
