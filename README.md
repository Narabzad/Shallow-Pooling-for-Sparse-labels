# Shallow-Pooling-for-Sparse-labels
Here you can find the crowdsourced judged data for first experiment in [Shallow pooling for sparse labels
](https://arxiv.org/abs/2109.00062) paper. 

For more details please check out section 3 of the paper.

![image](https://user-images.githubusercontent.com/43349991/133142682-61f43445-d804-4d68-b280-ec3ffd759cc2.png)

Data is given in the TSV format in [shallow_pooling_exp_1.tsv](https://github.com/Narabzad/Shallow-Pooling-for-Sparse-labels/blob/main/shallow_pooling_exp_1.tsv) for all 6980 queries in small dev set of msmarco and includes the following:
- query id
- query text
- Category ( A: when first ranked document from the selected run is qrel. B: When the first ranked document is not qrel)
- Prefrence (whether the judge prefered the qrel or the alternative document)
- qrel id
- qrel text
- alternative document id
- alternative document text
