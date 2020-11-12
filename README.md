# Implementation of apriori algorithm on transactional data
 Market basket data analysis using Data Mining techniques. This project uses Aprori algorithm for frequent itemset extraction. The min_support parameter is emperical.
 Frequent itemsets are extracted and association rules are derived. The longest rules are displayed although all of them are present in their respective vectors.

## Technique used
 * First the dataset's shape was changed. It was in the form of rows and converted to binary valued columns.

 * Then I used a minimum support value of 0.0075 to mine frequent itemsets. These itemsets were used to mine rules to predict items from one item.