# Data backend for http://het.io/disease-genes/

This repository hosts data for the following study,
which used heterogeneous network edge prediction to prioritize disease-associated genes:

> **Heterogeneous Network Edge Prediction: A Data Integration Approach to Prioritize Disease-Associated Genes**  
Daniel S. Himmelstein, Sergio E. Baranzini  
*PLOS Computational Biology* (2015-07-09) <https://doi.org/98q>  
DOI: [10.1371/journal.pcbi.1004259](https://doi.org/10.1371/journal.pcbi.1004259) · PMID: [26158728](https://www.ncbi.nlm.nih.gov/pubmed/26158728) · PMCID: [PMC4497619](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4497619)

Predictions from this project can be browsed at <https://het.io/disease-genes/>.
The [`browser`](browser) directory stores data files that are used by the browser webapp.
The `browser` directory was not designed to have a user-facing purpose.

The [`downloads`](downloads) directory hosts project-related datasets for user download.
Previousely, these downloads were documented at <https://het.io/disease-genes/downloads/>, but documentation has now moved to the README.

Most of the code for this study is available in the following repos: [het.io-dag-rcode](https://github.com/dhimmel/het.io-dag-rcode), [hetnetpy](https://github.com/hetio/hetnetpy), and [het.io-dag-pycode](https://github.com/dhimmel/het.io-dag-pycode).
