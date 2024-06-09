# Data source

This dataset is used  by Pol Castellano, autor and maintainer of the [fobitools](https://www.bioconductor.org/packages/release/bioc/html/fobitools.html) Bioconductor package, in one its vignettes, [Use Case ST000291](https://www.bioconductor.org/packages/release/bioc/vignettes/fobitools/inst/doc/MW_ST000291_enrichment.html).

Code for downloading the data using the MetabolomicsWorkbenchR package is available in the vignette,, but for consistency it is replicated in accompanying script `dataDownloadAndPrepare`

# Data description

The data consist of three separate files

- The features data
  - 1541 variables, 45 samples

- The metadata
  - 45 rows, two columns (sample name, group name)
  
The metabolite names
  - 1541 row, 3 columns (original name, PubChem ID and KEGG ID)

The data can be extracted manually from this dataset or as a Bioconductor Summarized Experiment dataset if it is read directly from Metabolomics Workbench database using Bioconductor [**`metabolomicsWorkbenchR`**](https://bioconductor.org/packages/release/bioc/vignettes/metabolomicsWorkbenchR/) package



