# Quora Retrieval System

A retrieval system for Quora. Given a new question (query), you want to find out the most similar questions that already exist (documents) in the Quora database, so that they can be shown as recommendations.

## Dataset format
➔ The dataset ‘Query_Doc’ contains 3 CSV files.\
➔ The ‘query’ file contains 100 query ids and query texts.\
➔ The ‘docs’ file contains 10,000 doc ids and doc texts.\
➔ The ‘qdrel’ file contains the query ids and the doc ids, if they are similar. 130 such relations are present in the file. Used this for evaluating the methods.

