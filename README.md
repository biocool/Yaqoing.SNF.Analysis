In this Proj. SNF (similarity network fusion) post-processing analysis are done focusing on cluster validity and robustness.
This clustering was done based on brain activity (fMRI) using three main language paradaigms and six clinical measures.
The main analysis are:
## 1- doing repeated cross-validation (using label propagation) to assess the accuracy of the cluster assignment.
## 2- Assessing the clustering robustness by randomly removing different pcnt of the data (repeatedly) and computing the normalized mutual information (NMI). 
## 3- Assigning the generalizablity of the clusters on the previous cohort (independent cohort with 60 subjects). 
Here you can find the R notebooks and their corresponding knitted HTM files
