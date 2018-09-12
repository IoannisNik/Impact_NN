# Impact_NN
Classifying impact on social media mentions, with the usage of neural networks

In order to run these notebooks:

1. You first need to have Jupyter installed on your computer, along with the libraries found on the import section.

2. The dataset should be of type excel.

3. Each dataset (Facebook, Twitter, Instagram) has specific features, to which you need to be compliant with, and in the order provided inside the dataset.



For the construction of the three datasets: 

1. You need to have an application on Facebook and Twitter. Then you can either write your own code for extracting the necessary fields, or use a tool like Facepager (https://github.com/strohne/Facepager).

2. Moreover you can use an instagram private api and write your own code for extracting data our of the sources of your interest (https://instagram-private-api.readthedocs.io/en/latest/index.html).

3. Remember that the only features you need are:
   - From Facebook: Total Reactions,Shares,Comments,Page_likes,Mention_type
   - From Twitter: favorite_count,retweet_count, user.followers_count (and find a way to extract replies as well, no known support method)
   - From Instagram: followers,likes,views,comments
