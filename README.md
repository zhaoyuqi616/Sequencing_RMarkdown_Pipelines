# Sequencing_RMarkdown_Pipelines

1) When login login Appolo cluster,

git clone git@github.com:zhaoyuqi616/Sequencing_RMarkdown_Pipelines.git

2) Modify the corresponding RMarkdown file in vi or interactive RStudio.
 
3) Then, run the pipeline using
Rscript -e "rmarkdown::render('example.Rmd',params=list(args = myarg))"![image](https://user-images.githubusercontent.com/14132861/161566904-9a2c0d46-ccf6-4178-b18c-225d0660b5b0.png)

The analytic pipelines for sequencing in IGC include:
1. RIP_seq_Pipeline.Rmd
2. RNA_seq_Analysis_Pipeline.Rmd
3. Seurat_scRNA_seq_Analysis.Rmd
4. m6A_seq_Analysis_Pipeline.Rmd
5. scVDJ_Analytic_Pipeline.Rmd
