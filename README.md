# Sequencing_RMarkdown_Pipelines

1) When login login Appolo cluster,

git clone git@github.com:zhaoyuqi616/Sequencing_RMarkdown_Pipelines.git

2) Modify the corresponding RMarkdown file in vi or interactive RStudio.
 
3) Then, run the pipeline using
Rscript -e "rmarkdown::render('example.Rmd',params=list(args = myarg))"

The current analytic pipelines for sequencing in IGC include:

1. RIP_seq_Pipeline.Rmd (Pipeline for RNA Immunoprecipitation Sequencing)
2. RNA_seq_Analysis_Pipeline.Rmd (Pipeline for RNA-seq)
3. Seurat_scRNA_seq_Analysis.Rmd (Pipeline for scRNA-seq)
4. m6A_seq_Analysis_Pipeline.Rmd (Pipeline for MeRIP-Seq, which maps m6A-methylated RNA)
5. scVDJ_Analytic_Pipeline.Rmd (Pipeline for single-cell V(D)J sequencing).
