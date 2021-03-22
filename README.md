# iiitd-training-work

Understanding the TCGA dataset obtained from Firehose browser. We obtained the latest processed data on 21-03-2021 from firehoseftb repository: http://gdac.broadinstitute.org/runs/stddata__2016_01_28/data/

The TCGA RNASeq downloaded contains
1. Rows represent the gene IDS
2. Column represent the sample names. For each sample there are three columns: raw_count, scaled_estimate	and transcript_id.
3. The starting geneids are of hypothetical protein genes therefore they start with  `?`.These are first 29 entries. [Source](https://www.biostars.org/p/91765/). The annotation file used for the TCGA dataset might be old therefore we didn't have HGNC symbols for these genes. Eg: > ?|100130426
>?|100133144
>?|100134869
>?|10357

4. TCGA clinical data: The information about the fields present in TCGA clinical data is described in the links given [here](https://www.biostars.org/p/126631/). The data dictionary of TCGA is available [here](https://docs.gdc.cancer.gov/Data_Dictionary/viewer/).
5. http://zyxue.github.io/2017/06/02/understanding-TCGA-mRNA-Level3-analysis-results-files-from-firebrose.html


| Hybridization REF | TCGA-3H-AB3K-01A-11R-A40A-07 | TCGA-3H-AB3K-01A-11R-A40A-07 | TCGA-3H-AB3K-01A-11R-A40A-07                                                                                                        | TCGA-3H-AB3L-01A-11R-A40A-07 | TCGA-3H-AB3L-01A-11R-A40A-07 | TCGA-3H-AB3L-01A-11R-A40A-07                                                                                                        |
| ----------------- | ---------------------------- | ---------------------------- | ----------------------------------------------------------------------------------------------------------------------------------- | ---------------------------- | ---------------------------- | ----------------------------------------------------------------------------------------------------------------------------------- |
| gene\_id          | raw\_count                   | scaled\_estimate             | transcript\_id                                                                                                                      | raw\_count                   | scaled\_estimate             | transcript\_id                                                                                                                      |

