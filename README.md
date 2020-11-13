# Market-Basket-Analysis-using-Apriori-Algorithm
Used Apriori Algorithm for Market Basket Analysis and made some amazing visualizations with seaborn, plotly, WordCloud, Squarify



Association Rule Mining

Market Basket Analysis is one of the key techniques used by large retailers to uncover associations between items. It works by looking for combinations of items that occur together frequently in transactions. To put it another way, it allows retailers to identify relationships between the items that people buy.

Association Rules are widely used to analyze retail basket or transaction data and are intended to identify strong rules discovered in transaction data using measures of interestingness, based on the concept of strong rules.


Apriori Algorithm

Apriori is an algorithm for frequent itemset mining and association rule learning over relational databases. It proceeds by identifying the frequent individual items in the database and extending them to larger and larger item sets as long as those item sets appear sufficiently often in the database. The frequent itemsets determined by Apriori can be used to determine association rules which highlight general trends in the database: this has applications in domains such as market basket analysis.


Some important terms:

Support: This says how popular an itemset is, as measured by the proportion of transactions in which an itemset appears.

Confidence: This says how likely item Y is purchased when item X is purchased, expressed as {X -> Y}. This is measured by the proportion of transactions with item X, in which item Y also appears.

Lift: This says how likely item Y is purchased when item X is purchased while controlling for how popular item Y is.



fig = px.sunburst(market, path=['year', 'month', 'day_of_week'],title="Don't forget to bring the cursor on the chart")
fig.show()

