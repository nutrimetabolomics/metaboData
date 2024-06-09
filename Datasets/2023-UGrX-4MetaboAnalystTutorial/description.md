This dataset is used  by Sara Herraiz in a tutorial on metabolomics data analysis using MetaboAnalyst.

The data have been downloaded from Metabolomics Workbench and their ID is in the file

The data file is a text (.txt) file structured in two blocks

- Information abot the study and the data: rows 1:70

- The data in recrtangular form : rows 71 and below

The data can be extracted manually from this dataset or as a Bioconductor Summarized Experiment dataset if it is read directly from Metabolomics Workbench database using Bioconductor [**`metabolomicsWorkbenchR`**](https://bioconductor.org/packages/release/bioc/vignettes/metabolomicsWorkbenchR/) package


In order to preprare the data for the analysis some cleaning is performed on the data.
- Remove metadata Information
	-From first rows
- Remove metabolites names
	- From last rows
- Change Factor labels to Before / After
- Add a letter (B / A) to each sample label, to show to which group it belongs
- Save file as .csv naming it 