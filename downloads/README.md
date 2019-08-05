# Disease-Associated Genes Prediction Downloads

This directory contains datasets related to the study:

> **Heterogeneous Network Edge Prediction: A Data Integration Approach to Prioritize Disease-Associated Genes**  
Daniel S. Himmelstein, Sergio E. Baranzini  
*PLOS Computational Biology* (2015-07-09) <https://doi.org/98q>  
DOI: [10.1371/journal.pcbi.1004259](https://doi.org/10.1371/journal.pcbi.1004259) · PMID: [26158728](https://www.ncbi.nlm.nih.gov/pubmed/26158728) · PMCID: [PMC4497619](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4497619)

Previousely, these downloads were described at <https://het.io/disease-genes/downloads/>.
In August 2019, we moved the downloads documentation to this README.
Many of these downloads are also available as Supporting Information files from _PLOS Computational Biology_, as indicated by the corresponding DOI links.

## Predictions

- **Predictions** — [`predictions.txt.gz`](predictions.txt.gz)  
Predicted probabilities of association between all genes (rows) and diseases (columns).  
PLOS **S1 Data** at <https://doi.org/10.1371/journal.pcbi.1004259.s013>

- **Features** — [`features.txt.gz`](features.txt.gz)  
The features (columns) computed for each gene-disease pair (rows).
Column names with beginning with 'XB' refer to standardized features.

- **Model Coefficients** — [`coefficients.txt`](coefficients.txt)  
Standardized and unstandardized coefficients from the ridge and lasso logistic regression models.

## Resources

- **Protein-coding Genes** — [`genes.txt`](genes.txt)  
Information on the included protein-coding genes, derived from the HGNC database.  
PLOS **S3 Data** at <https://doi.org/10.1371/journal.pcbi.1004259.s015>

- **Complex Diseases** — [`diseases.txt`](diseases.txt)  
All diseases with at least one GWAS-Catalog-extracted association.
The manual pathophysiology classification is included.  
PLOS **S6 Data** at <https://doi.org/10.1371/journal.pcbi.1004259.s018>

- **Tissue-specific Gene Expression** — [`expression.txt.gz`](expression.txt.gz)  
A processed version of the GNF BodyMap providing a gene's (row, HGNC symbols) expression value for each of 77 tissues (columns, BRENDA Tissue Ontology IDs).  
PLOS **S9 Data** at <https://doi.org/10.1371/journal.pcbi.1004259.s021>

- **Gene-Disease Associations** — [`gene-associations.txt`](gene-associations.txt)  
All gene-disease associations extracted from the GWAS catalog for the four categories of association.  
PLOS **S5 Data** at <https://doi.org/10.1371/journal.pcbi.1004259.s017>

- **Processed GWAS Catalog Loci** — [`loci-associations.txt`](loci-associations.txt)  
The associated gene-disease loci (regions) derived from the GWAS Catalog.  
PLOS **S4 Data** at <https://doi.org/10.1371/journal.pcbi.1004259.s016>

- **Disease Localization** — [`disease-localization.txt`](disease-localization.txt)  
Literature co-occurrence between diseases and tissues calculated using CoPub 5.0.  
PLOS **S10 Data** at <https://doi.org/10.1371/journal.pcbi.1004259.s022>

- **Protein-Protein Interactions** — [`protein-interactions.txt.gz`](protein-interactions.txt.gz)  
Protein-protein interactions processed from iRefIndex using ppiTrim.
ppiTrim converts to gene space, consolidates duplicate interactions, and removes complexes.
PLOS **S8 Data** at <ttps://doi.org/10.1371/journal.pcbi.1004259.s020>

## Network

- **Serialized Network** — [`network.json.gz`](network.json.gz)  
A JSON formatted text file storing the complete network.
The top level is an JSON object with four pairs (metanodes, metaedges, nodes, edges).
The value for each pair is a JSON array containing the corresponding items.

- **Network Tables** — [`network-tables.zip`](network-tables.zip)  
A table of network edges (sif format) and a table of node attributes.  
PLOS **S2 Data** at <https://doi.org/10.1371/journal.pcbi.1004259.s014>

## Visualization

- **Vector Images** — [`figures.zip`](figures.zip)  
PDF formatted versions of the figures.  
PLOS **S13 Data** at <https://doi.org/10.1371/journal.pcbi.1004259.s025>
