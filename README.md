# AtNE-Trust
# AtNE-Trust: Attributed Trust Network Embedding for Trust Predicrion in Online Social Networks

Datasets: Epinions and Ciao datasets are used in this paper. The raw datasets are available at: http://www.cse.msu.edu/~tangjili/trust.html

Epinions and Ciao datasets contain several information to fufill our algorithm. The input of our paper are as follows:
1. trust relationships (trustor, trustee, trust_value)
2. rating values (u, v, rating)
3. reviews (u, v, reviews)
4. items(v, content, category)

u represents users, v represents items. There are also detail information about items including their contents and categories.



Run our algorithm with the following steps:
1. generate trust network embedding with "trust_network_embedding"
2. generate attributes embedding with "MF" and "Doc2Vec"
3. run main code "AtNE-Trust/atne_trust"

u represents users, v represents items. There are also detail information about items including contents, categories.

Note that in our code, we read trust relationships data directly from the database. And we output these data in ".txt" form. Code can easily revised if the ".txt" form files are directly fed into it.
