# Data-Visualization-using-TSNE
For Data Visualization , one of the best dimensional reduction algorithm is TSNE. Here I use AMAZON FINE FOOD REVIEWS and perform TSNE algorithm on Text features by converting them in vectors using BOW, TFIDF, AVG-W2V &amp; TFIDF-W2V
Always check for multiple value of perplexity as shown in above, I use perplexities = [2,5,10,30,50,100].
In above Program I use TSNE Algorithm for dimensional reduction on AMAZON FINE FOOD REVIEWS dataset. First, Convert text reviews into vectors using BOW, TF-IDF, Avg-W2V, TFIDF-W2V.

It is seen for perplexity = 30 or 50 data is fairly spread without any much outliers. Also it is good to use TFIDF-W2V and W2V than others.

[NOTE : The learning rate for t-SNE is usually in the range [10.0, 1000.0]. If the learning rate is too high, the data may look like a ‘ball’ with any point approximately equidistant from its nearest neighbours. If the learning rate is too low, most points may look compressed in a dense cloud with few outliers. If the cost function gets stuck in a bad local minimum increasing the learning rate may help.]
