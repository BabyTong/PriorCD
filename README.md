# PriorCD
> > > > > > PriorCD: Prioritizing Cancer Drugs for Interested Cancer



Prioritize candidate cancer drugs for drug repositioning based on the random walk with restart algorithm in a drug-drug functional similarity network. 1) We firstly constructed a drug-drug functional similarity network by integrating pathway activity and drug activity derived from the NCI-60 cancer cell lines. 2) Secondly, we calculated drug repurposing score according to a set of approved therapeutic drugs of interested cancer based on the random walk with restart algorithm in the drug-drug functional similarity network. 3) Finally, the permutation test was used to calculate the statistical significance level for the drug repurposing score.



- This package provides the `prior` function to prioritize candidate drugs against interested cancer.
- This package provides the `drsim` function to convert correlation matrix into binary drug similarity adjacency mattrix.
- This package provides the `getROC` function to calculate AUC and plot ROC curve of your result.
- This package provides the `getDNN` function to show the network sturcture of the therapeutic drugs used to prioritize and drug candidates that have been prioritized.