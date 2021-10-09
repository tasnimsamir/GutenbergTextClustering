# GutenbergTextClustering
Text clustering is a method of processing the unlabeled texts into groups or clusters therefore this NLP analysis is called text clustering.It is one of the unsupervised learning techniques that depends on grouping the texts according to their similarity. Imagine you are a librarian and you want to group the books into grouos and subgroups according to their similarity on their authors and their scopes as well [1]. In this project, Text Clustering pipeline consists of five main components:

* Data Cleaning: this step includes uploding gutenberg's five books with different genres and different authors. The selected geres are: Fiction, Mystery, Science, Detective, and Novel.

* Data Partitioning: the raw text books are partioned into 200 partitions randomly. each partition consists of 150 words.

* Feature Engineering: the raw dataset is transformed into vectors that can be used in a machine learning model. this step includes creating new features.

* Clustering: training different clustering algorithms for further selecting the best algorithm.

* Evaluation: if this clustering define separations of the data similar to some ground truth set of classes or satisfying some assumption such that members belong to the same class are more similar than members of different classes according to some similarity metric.

I used different feature engineering techniques with different clustering algorithms to select the champoin clusterer in the end. in addition, i did some clustering performance evaluations to measure different parametes as: Silhouette Coefficient to determine the better defined clusters, cohen's kappa to measure the inter-agreement, v-measure to measure the homogenity and completeness of the clustering, and normalized mutual information score to measure the coherence between the clusters. Finally i did some error analysis like Principal component analysis (PCA) visualization to the best clusterer, and top 10 frequent words to the mislabeled partition.
