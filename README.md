# Topic-Summarization-Search-Engine
•Full-scale search engine consisted of a front-end website(JavaScript) along with Apache Solr back-end which is used to index Twitter’s unstructured data.

•Search Engine used Latent Dirichlet Allocation sub-topic model to operate on half a million crawled tweets data across 5 language. Model used this tweet data for model training and then clustered tweets based on similarity of topics.

•Wiki and pixabay APIs are used for generating static Summaries and for graphical images respectively for user-queries.

•This search engine presents user with a web interface(Hosted on Apache Solr) to enter desired query and in response presented user with the static summary retrieved using wiki and pixabay APIs as well as dynamic summary composed using relevant tweets using above LDA model.
