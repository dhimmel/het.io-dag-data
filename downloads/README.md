# Disease-Associated Genes Prediction Downloads

This directory contains datasets related to the study:

> **Heterogeneous Network Edge Prediction: A Data Integration Approach to Prioritize Disease-Associated Genes**  
Daniel S. Himmelstein, Sergio E. Baranzini  
*PLOS Computational Biology* (2015-07-09) <https://doi.org/98q>  
DOI: [10.1371/journal.pcbi.1004259](https://doi.org/10.1371/journal.pcbi.1004259) · PMID: [26158728](https://www.ncbi.nlm.nih.gov/pubmed/26158728) · PMCID: [PMC4497619](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4497619)

Previousely, these downloads were described at <https://het.io/disease-genes/downloads/>.
In August 2019, we moved the downloads documentation to this README.

Many of these downloads are also available as Supporting Information files from _PLOS Computational Biology_, as indicated by the corresponding DOI links.
Where the Supporting Information files use as `.txt` extension, the downloads here have switched to `.tsv` when appropriate for better GitHub previewing.

The first two rows are shown below for each TSV download.
These previews were generated by [`create-markdown-previews.ipynb`](create-markdown-previews.ipynb).

## Predictions

- **Predictions** — [`predictions.tsv.gz`](predictions.tsv.gz)  
Predicted probabilities of association between all genes (rows) and diseases (columns).  
PLOS **S1 Data** at <https://doi.org/10.1371/journal.pcbi.1004259.s013>

    gene_symbol | age related macular degeneration | Alzheimer's disease | ankylosing spondylitis | asthma | atopic dermatitis | bipolar disorder | breast carcinoma | celiac disease | chronic lymphocytic leukemia | coronary artery disease | Crohn's disease | Graves' disease | lung carcinoma | metabolic syndrome X | migraine | multiple sclerosis | obesity | Parkinson's disease | primary biliary cirrhosis | prostate carcinoma | psoriasis | refractive error | rheumatoid arthritis | schizophrenia | systemic lupus erythematosus | type 1 diabetes mellitus | type 2 diabetes mellitus | ulcerative colitis | vitiligo
    --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | ---
    A1BG | 0.000902865316849012 | 0.000843094981697786 | 0.000865232781366083 | 0.000831379132325189 | 0.000911703492360143 | 0.000808922207291462 | 0.000959152333696821 | 0.000863317239021426 | 0.000883366400989101 | 0.000860652442140361 | 0.00101527849738045 | 0.000834690712259122 | 0.000836175784541967 | 0.000890262249489595 | 0.000910202482110256 | 0.000942966382621634 | 0.000885761201398873 | 0.00108242243839361 | 0.000877403291771053 | 0.000955266902171645 | 0.000836837597339859 | 0.000867033176122321 | 0.000913629510226676 | 0.000900995771178386 | 0.00088691653115335 | 0.000925299177993949 | 0.000918381930484204 | 0.000894170209705782 | 0.000883307183575619
    A1CF | 0.000957085997890059 | 0.000931608757521376 | 0.000846946668196247 | 0.000896742727312265 | 0.000885461144158393 | 0.000880761040241341 | 0.00118376663378837 | 0.000937125303326467 | 0.0010001122696522 | 0.00103019822337742 | 0.00115055855886886 | 0.000884716707004226 | 0.000961631136752842 | 0.00108022768862733 | 0.000942302096046314 | 0.00107627566455975 | 0.000966189226666171 | 0.000871368013059514 | 0.000955566329246775 | 0.00103882600872266 | 0.000926214620214113 | 0.000865329148260458 | 0.000976980091510641 | 0.000976109228605849 | 0.000937952065921 | 0.00100576569571365 | 0.00116644271736648 | 0.000945200666696613 | 0.000906560576575734

- **Features** — [`features.tsv.gz`](features.tsv.gz)  
The features (columns) computed for each gene-disease pair (rows).
Column names with beginning with 'XB' refer to standardized features.

    gene_code | gene_symbol | disease_code | disease_name | status | status_int | percentile | part | PC_s\|G-a-D | PC_t\|G-a-D | DWPC_0.4\|G-e-T-l-D | DWPC_0.4\|G-i-G-a-D | DWPC_0.4\|G-m-C5.B-m-G-a-D | DWPC_0.4\|G-m-C2.CP.K-m-G-a-D | DWPC_0.4\|G-m-C2.CP.B-m-G-a-D | DWPC_0.4\|G-m-C3.T-m-G-a-D | DWPC_0.4\|G-m-C1-m-G-a-D | DWPC_0.4\|G-m-C3.M-m-G-a-D | DWPC_0.4\|G-m-C4.CG-m-G-a-D | DWPC_0.4\|G-m-C4.CM-m-G-a-D | DWPC_0.4\|G-a-D-a-G-a-D | DWPC_0.4\|G-a-D-m-P-m-D | DWPC_0.4\|G-a-D-l-T-l-D | DWPC_0.4\|G-m-C5.M-m-G-a-D | DWPC_0.4\|G-m-C2.CG-m-G-a-D | DWPC_0.4\|G-m-C2.CP.R-m-G-a-D | DWPC_0.4\|G-m-C7-m-G-a-D | DWPC_0.4\|G-m-C6-m-G-a-D | DWPC_0.4\|G-e-T-e-G-a-D | DWPC_0.4\|G-i-G-e-T-l-D | DWPC_0.4\|G-i-G-i-G-a-D | DWPC_0.4\|G-m-C5.C-m-G-a-D | disease_pathophys | ridge | lasso | XB\|PC_s\|G-a-D | XB\|PC_t\|G-a-D | XB\|DWPC_0.4\|G-e-T-l-D | XB\|DWPC_0.4\|G-i-G-a-D | XB\|DWPC_0.4\|G-m-C5.B-m-G-a-D | XB\|DWPC_0.4\|G-m-C2.CP.K-m-G-a-D | XB\|DWPC_0.4\|G-m-C2.CP.B-m-G-a-D | XB\|DWPC_0.4\|G-m-C3.T-m-G-a-D | XB\|DWPC_0.4\|G-m-C1-m-G-a-D | XB\|DWPC_0.4\|G-m-C3.M-m-G-a-D | XB\|DWPC_0.4\|G-m-C4.CG-m-G-a-D | XB\|DWPC_0.4\|G-m-C4.CM-m-G-a-D | XB\|DWPC_0.4\|G-a-D-a-G-a-D | XB\|DWPC_0.4\|G-a-D-m-P-m-D | XB\|DWPC_0.4\|G-a-D-l-T-l-D | XB\|DWPC_0.4\|G-m-C5.M-m-G-a-D | XB\|DWPC_0.4\|G-m-C2.CG-m-G-a-D | XB\|DWPC_0.4\|G-m-C2.CP.R-m-G-a-D | XB\|DWPC_0.4\|G-m-C7-m-G-a-D | XB\|DWPC_0.4\|G-m-C6-m-G-a-D | XB\|DWPC_0.4\|G-e-T-e-G-a-D | XB\|DWPC_0.4\|G-i-G-e-T-l-D | XB\|DWPC_0.4\|G-i-G-i-G-a-D | XB\|DWPC_0.4\|G-m-C5.C-m-G-a-D
    --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | ---
    HGNC:5 | A1BG | DOID:10286 | prostate carcinoma | negative | 0 | 0.10572593 | train | 0 | 34 | 0 | 0 | 0 | 0 | 0 | 0.00155245904597262 | 0 | 0 | 0 | 0.0020210045278042 | 0 | 0 | 0 | 0 | 0.00121789583242957 | 0 | 0 | 0 | 0.00089748671759056 | 0.0019959656678926 | 0 | 0.00411933832386317 | neoplastic | 0.000955266902171645 | 0.000904602830537589 | 0 | 0.0578418829928233 | 0 | 0 | 0 | 0 | 0 | 0.0220756680131442 | 0 | 0 | 0 | 0.0289325302452683 | 0 | 0 | 0 | 0 | 0.0400509738187678 | 0 | 0 | 0 | 0.00401721262818795 | 0.00350152338505844 | 0 | 0.0405191297120283
    HGNC:24086 | A1CF | DOID:10286 | prostate carcinoma | negative | 0 | 0.59621654 | train | 0 | 34 | 0.00590021447147218 | 0 | 0.00619975385355829 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0.000645118666484247 | 0 | 0.00111228506784582 | 0 | 0.00483938065794723 | 0.00469503472779078 | 0 | 0.00268768008923857 | neoplastic | 0.00103882600872266 | 0.000846424494832754 | 0 | 0.0578418829928233 | 0.0173638829936915 | 0 | 0.0974203041285678 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0.0212149759719727 | 0 | 0.030702468640466 | 0 | 0.0216614025708436 | 0.00823650133740952 | 0 | 0.0264368812654755

- **Model Coefficients** — [`coefficients.tsv`](coefficients.tsv)  
Standardized and unstandardized coefficients from the ridge and lasso logistic regression models.

    feature | name | ridge_coef | ridge_zcoef | lasso_coef | lasso_zcoef | select_coef | select_zcoef
    --- | --- | --- | --- | --- | --- | --- | ---
    DWPC_0.4\|G-a-D-a-G-a-D | GaDaGaD | 50.1059419658922 | 2.53778862460897 | 58.1870914234121 | 2.94708637179072 | 57.449958914982 | 2.90975174796513
    DWPC_0.4\|G-a-D-l-T-l-D | GaDlTlD | 20.5895169007358 | 2.00413247793486 | 26.8769993619278 | 2.61614041700751 |  | 

## Resources

- **Protein-coding Genes** — [`genes.tsv`](genes.tsv)  
Information on the included protein-coding genes, derived from the HGNC database.  
PLOS **S3 Data** at <https://doi.org/10.1371/journal.pcbi.1004259.s015>

    hgnc_id | symbol | name | aliases | entrez | ensembl | uniprot | chromosome
    --- | --- | --- | --- | --- | --- | --- | ---
    HGNC:5 | A1BG | alpha-1-B glycoprotein |  | 1 | ENSG00000121410 | P04217 | 19q13.43
    HGNC:24086 | A1CF | APOBEC1 complementation factor | ACF\|ACF64\|ACF65\|APOBEC1CF\|ASP | 29974 | ENSG00000148584 | Q9NQ94 | 10q21.1

- **Processed GWAS Catalog Loci** — [`loci-associations.tsv`](loci-associations.tsv)  
The associated gene-disease loci (regions) derived from the GWAS Catalog.  
PLOS **S4 Data** at <https://doi.org/10.1371/journal.pcbi.1004259.s016>

    disease_code | disease_name | resolved_gene | confidence | candidate_genes | report_counter | mapped_genes | dapple_genes | studies | snps | mlog_pvals
    --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | ---
    DOID:1686 | glaucoma | CDKN2B | HC | CDKN2B | Counter({CDKN2B: 2}) | None\|None\|None\|CDKN2B\|None\|None | CDKN2B\|CDKN2A\|MTAP | 22570617\|21532571\|22570617\|22419738\|22428042\|22792221 | rs2157719\|rs4977756\|rs2157719\|rs1063192\|rs7865618\|rs523096 | 17.699\|14.000\|12.000\|10.301\|10.046\|10.301
    DOID:1686 | glaucoma | TMCO1 | HC | TMCO1\|ALDH9A1 | Counter({TMCO1: 1}) | TMCO1 | UCK2\|MGST3\|ALDH9A1\|TMCO1 | 21532571 | rs4656461 | 13.222

- **Gene-Disease Associations** — [`gene-associations.tsv`](gene-associations.tsv)  
All gene-disease associations extracted from the GWAS catalog for the four categories of association.  
PLOS **S5 Data** at <https://doi.org/10.1371/journal.pcbi.1004259.s017>

    disease_code | disease_name | gene_code | gene_symbol | status
    --- | --- | --- | --- | ---
    DOID:10652 | Alzheimer's disease | HGNC:37 | ABCA7 | HC_primary

- **Complex Diseases** — [`diseases.tsv`](diseases.tsv)  
All diseases with at least one GWAS-Catalog-extracted association.
The manual pathophysiology classification is included.  
PLOS **S6 Data** at <https://doi.org/10.1371/journal.pcbi.1004259.s018>

    Disease | Code | Pathophysiology | HC-P | HC-S | LC-P | LC-S
    --- | --- | --- | --- | --- | --- | ---
    Crohn's disease | DOID:8778 | immunologic | 67 | 179 | 4 | 2
    multiple sclerosis | DOID:2377 | immunologic | 50 | 43 | 38 | 29

- **Protein-Protein Interactions** — [`protein-interactions.tsv.gz`](protein-interactions.tsv.gz)  
Protein-protein interactions processed from iRefIndex using ppiTrim.
ppiTrim converts to gene space, consolidates duplicate interactions, and removes complexes.
PLOS **S8 Data** at <ttps://doi.org/10.1371/journal.pcbi.1004259.s020>

    source_code | source_symbol | target_code | target_symbol | pubmed | interaction_type | method
    --- | --- | --- | --- | --- | --- | ---
    HGNC:5 | A1BG | HGNC:545 | ANXA7 | 21900206 | MI:0407(direct interaction) | MI:0018(two hybrid)
    HGNC:5 | A1BG | HGNC:1784 | CDKN1A | 21900206 | MI:0407(direct interaction) | MI:0018(two hybrid)

- **Tissue-specific Gene Expression** — [`expression.tsv.gz`](expression.tsv.gz)  
A processed version of the GNF BodyMap providing a gene's (row, HGNC symbols) expression value for each of 77 tissues (columns, BRENDA Tissue Ontology IDs).  
PLOS **S9 Data** at <https://doi.org/10.1371/journal.pcbi.1004259.s021>

    BTO:0000038 | BTO:0000041 | BTO:0000045 | BTO:0000047 | BTO:0000084 | BTO:0000089 | BTO:0000141 | BTO:0000142 | BTO:0000211 | BTO:0000232 | BTO:0000269 | BTO:0000289 | BTO:0000293 | BTO:0000443 | BTO:0000562 | BTO:0000614 | BTO:0000651 | BTO:0000664 | BTO:0000671 | BTO:0000725 | BTO:0000738 | BTO:0000755 | BTO:0000759 | BTO:0000763 | BTO:0000776 | BTO:0000784 | BTO:0000873 | BTO:0000876 | BTO:0000914 | BTO:0000958 | BTO:0000961 | BTO:0000975 | BTO:0000988 | BTO:0000991 | BTO:0001001 | BTO:0001042 | BTO:0001067 | BTO:0001073 | BTO:0001078 | BTO:0001101 | BTO:0001103 | BTO:0001129 | BTO:0001154 | BTO:0001175 | BTO:0001176 | BTO:0001203 | BTO:0001231 | BTO:0001235 | BTO:0001253 | BTO:0001256 | BTO:0001260 | BTO:0001264 | BTO:0001279 | BTO:0001325 | BTO:0001355 | BTO:0001363 | BTO:0001365 | BTO:0001374 | BTO:0001379 | BTO:0001385 | BTO:0001387 | BTO:0001388 | BTO:0001424 | BTO:0001539 | BTO:0001561 | BTO:0002042 | BTO:0002246 | BTO:0002252 | BTO:0002320 | BTO:0002417 | BTO:0002807 | BTO:0002924 | BTO:0003335 | BTO:0003975 | BTO:0004238 | BTO:0004730 | BTO:0004911
    --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | ---
    4 | 4.05 | 4.15 | 4.1 | 4 | 4.1 | 4.1 | 4 | 4.2 | 4.12492424172857 | 4.05 | 4 | 4.1 | 4.1 | 3.7 | 4.05 | 4.1 | 4.1 | 4.1 | 4.15 | 4.1 | 4.05 | 8898.60000000001 | 4.05 | 4 | 4.1 | 4.05 | 4.1 | 4 | 4 | 4.05 | 4.1 | 4.1 | 4.1 | 4.1 | 3.9 | 4.06998771496917 | 4.1 | 4.05 | 4.1 | 4.1 | 4.1 | 3.65 | 3.95 | 4.05 | 4.1 | 4.05 | 4.05 | 4.05 | 4.05 | 4.05 | 4.05 | 4.1 | 3.95 | 4.1 | 4.05 | 4.2 | 4.05 | 4 | 4.1 | 4.1 | 4.1 | 4.04969134626332 | 3.1 | 4.05 | 4.1 | 4.1 | 4.1 | 4 | 4 | 3.8 | 4.1 | 4 | 4.1 | 4.05 | 4.05 | 4.1
    48.55 | 63.05 | 86.1 | 60.05 | 92.1 | 60.7 | 80.35 | 40.45 | 52.6 | 69.7784350641371 | 237.25 | 27.55 | 37.3 | 41.15 | 60.1 | 64 | 242.95 | 39.25 | 131.65 | 20.2 | 39.55 | 62.85 | 362.4 | 53.45 | 22.05 | 41.9 | 40.25 | 23.1 | 33.2 | 39.15 | 55.9 | 72.85 | 215.05 | 269.9 | 57.1 | 52.95 | 37.207741130039 | 77.45 | 52.25 | 69.1 | 101.3 | 51.25 | 87.4 | 53.85 | 28.5 | 47.15 | 81.35 | 50.25 | 69.85 | 42.15 | 45.35 | 46.75 | 53.25 | 107.2 | 42.4 | 74.45 | 46.5 | 37.6 | 69.65 | 79.95 | 44.85 | 42.6 | 63.9411839114666 | 64.15 | 63.75 | 24.45 | 31.15 | 37.65 | 58.2 | 30.2 | 44.85 | 48.9 | 41.1 | 58.2 | 37.3 | 17.35 | 31.6

- **Disease Localization** — [`disease-localization.tsv`](disease-localization.tsv)  
Literature co-occurrence between diseases and tissues calculated using CoPub 5.0.  
PLOS **S10 Data** at <https://doi.org/10.1371/journal.pcbi.1004259.s022>

    doid_id | doid_name | bto_id | bto_name | r_scaled
    --- | --- | --- | --- | ---
    DOID:10652 | Alzheimer's disease | BTO:0000776 | B-lymphocyte | 23.0
    DOID:10652 | Alzheimer's disease | BTO:0000755 | Leydig cell | 21.0

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
