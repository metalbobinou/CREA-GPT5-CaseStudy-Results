# CREA-GPT5-CaseStudy-Results

Public results of the case study between CREA and GPT5.

This repository is expected to be moved to a public open archive.


## Organization:

* __input__: contains the two main inputs used (original data from CREA and the clusters, and references to the papers used in the study)
* __intermediate__: contains the intermediate results (statistics on inputs, and clusters size)
* __output__: contains the outputs, which are the clusters produced in different configurations


## Output:

__Filename__: [Dataset]-[Strategy]-[Beta]-[Clustering (k)]

_Dataset_: PHPCourses, Abstracts, FullPapers

_Strategy_: High (H), Medium (M), Low (L), Direct (D)

_Beta_: The Beta chosen

_Clustering (k)_: The number of clusters given (the k value)


e.g.: Abstracts-Clusters-S=M-B=1.00-k=16.csv

Concerns the _Abstracts_ dataset, with the _medium strategy_ using a _Beta of 1.00_, and asking for _16 clusters (k=16)_.
