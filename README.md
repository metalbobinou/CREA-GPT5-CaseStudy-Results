# CREA-GPT5-CaseStudy-Results

Public results of the case study between CREA and GPT5.

This repository is expected to be moved to a public open archive.


## Organization:

* __input__: contains the two main inputs used (original data from CREA and the clusters, and references to the papers used in the study)
* __intermediate__: contains the intermediate results (statistics on inputs, and clusters size)
* __output__: contains the outputs, which are the clusters produced in different configurations


## Output:

__Filename__ (CREA case) : [Dataset]-Clusters-[Strategy]-[Beta]-[Clustering (k)]

__Filename__ (GPT5 case) : [Dataset]-Clusters-GPT-[Clustering (k)]

_Dataset_: PHPCourses, Abstracts, FullPapers

_Strategy_: High (H), Medium (M), Low (L), Direct (D)

_Beta_: The Beta chosen

_Clustering (k)_: The number of clusters given (the k value)


Example 1: Abstracts-Clusters-S=M-B=1.00-k=16.csv

Concerns the _Abstracts_ dataset processed with CREA, with the _medium strategy_ using a _Beta of 1.00_, and asking for _16 clusters (k=16)_.


Example 2: FullPapers-Clusters-GPT-k=8.csv

Concerns the _FullPapers_ dataset processed with ChatGPT, asking for _8 clusters (k=8)_.
