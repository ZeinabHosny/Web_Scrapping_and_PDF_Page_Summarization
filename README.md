#### This task was about:

- web scrapping 

- summarize page in a pdf

#### PDF Page Summarization Steps using the sentence embdding method

1. Reading the Page content then printing it.
2. Cleaning the Page content then printing it.
3. Splitting into sentences (Tokenization) but the last sentence is removed and also the sentences which smaller than 5 words then printing all the chosen sentences.
4. Vectorizing each sentence using TF-Hub Universal sentence Encoder (embedding matrix).
5. Applaying Kmeans clusturing to cluster the sentences into certain no. of clusters.
6. Forming Page summary from the sentences which are the nearst to clusteres centroids. from each cluster we take a sentence; this sentence is the closest to the centroid. Then we join these sentences together to form the summary.
7. Printing the summary of The Page.
