Data used in the paper "dentifying subgroups of childhood obesity by using multiplatform metabotyping"

The data has been reposited in Metabolomics Worknbench with 

- Project ID:	PR001863
- Project DOI:	doi: 10.21228/M8WX4S

Although the paper refers to clinical, genetic and metabolomic data only the former (metabolomic) seem to be available.

Metabolimic data are described in the "Data" 

https://www.metabolomicsworkbench.org/data/DRCCMetadata.php?Mode=Study&DataMode=MSData&StudyID=ST002993&StudyType=MS&ResultType=5#DataTabs

There are 5 datsets mentioned (and 5 metadata files) available but only 4 metabolites "Results" so the missing file is ignored.


File: `code/Reanálisis_de_resultados_procesados-Estudio_ST002993.html` describes the preprocess done with the files, available in the "data" directory.

The resulting objects are

- A `SummarizedExperiment`object with the preprocessed and normalized data as well as the metadata for rows (platforms) and columns (obesity type).
- A `results_filtered_normalized.csv` text file with the 892 (metabolites) x 110 (samples) data.
- A file `factor_matrix.csv` with a  5 (latent factors) x 110 (samples)   matrix produced by the multiple factor analysis that can be taken as the basis for metabotype construction. 

