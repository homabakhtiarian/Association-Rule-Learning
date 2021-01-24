# Apriori and Eclat

*People who bought ... also bought ...*

Association rule learning is a rule-based machine learning method for discovering interesting relations between variables in large databases.

This rule shows how frequently a itemset occurs in a transaction. A typical example is Market Based Analysis.

Market Based Analysis is one of the key techniques used by large relations to show associations between items.It allows retailers to identify relationships between the items that people buy together frequently.

Given a set of transactions, we can find rules that will predict the occurrence of an item based on the occurrences of other items in the transaction.

### Basic definitions:

- Support — Indication of how frequently the itemset appears in the database. It is defined as the fraction of records that contain X?Y to the total number of records in the database. Suppose, the support of an item is 0.1%, it means only 0.1% of the transactions contain that item.
Support (XY) = Support count of (XY) / Total number of transaction in D

- Confidence — Fraction of the number of transactions that contain X?Y to the total number of records that contain X.
It’s is a measure of the strength of the association rules.
Suppose, the confidence of the association rule X?Y is 80%, it means that 80% of the transactions that contain X also contain Y together.
Confidence (X|Y) = Support (XY) / Support (X)

- Other measures include Lift, Conviction, All-Confidence, Collective strength and Leverage.

### Difference between Apriori and Eclat:

- Apriori are use large dataset and eclat are small and medium datase.

- Apriori are scan orignal(real) dataset Eclat scan currently genereted dataset.

- Apriori are slower then Eclat.

- In Apriori we need to add Support, Confidence But in Eclat only we need to give Support.
