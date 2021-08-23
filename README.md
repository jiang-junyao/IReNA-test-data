# IReNA test data
## scRNA-seq folder:
scRNA-seq test data, if you want to run IReNA test, you just need to download **seurat_object**. Kmeans_clustering_ENS.txt and, regulatory_relationships.txt and filtered_regulatory_relationships.txt are consequence of IReNA part1, which can be used to check whether your consequence is correct.

**seurat_object.rds**: seurat object, use readRDS() to load it

**Kmeans_clustering_ENS.txt**: consequence of add_ENSID() function

**regulatory_relationships.txt**: consequence of get_cor() function

**filtered_regulatory_relationships.txt**: consequence of filter_regulatory() function in Part2 of IReNA


## bulk RNA-seq folder:
bulk RNA-seq test data

**test_data_RNA-seq.txt**: raw counts of bulk RNA-seq

## ATAC-seq folder
bam file of each sample, differential peaks file of all samples, footprints file of all samples

**SSC1_filter.bam, SSC2_filter.bam, esc_filter.bam**: bam file generated in step11 of [ATAC-seq pipline](https://github.com/jiang-junyao/ATAC-seq-pipline)

**differential_peaks.bed**：differential peaks generated in step8 of [ATAC-seq pipline](https://github.com/jiang-junyao/ATAC-seq-pipline)

**footprints.bed**: footprints file generated in step10 of [ATAC-seq pipline](https://github.com/jiang-junyao/ATAC-seq-pipline)
