# Cell Class Features
Cell class genomic and epigenetic features for Lineage Tracing.

# Data Source
Dataframe for analysis is from `microb215.med.upenn.edu:/Users/berry/Public/WAS/fdr-empir.csv`,
column described in `oct25-facs-fdr.pdf` section 5.1.

# Results 
Standard heatmap figures are in 'genomic_heatmap' and 'epi_heatmap' folders.

# Document Generation

In bash:
```
Rscript -e "rmarkdown::render('heatmaps.Rmd', 'pdf_document')"
```
