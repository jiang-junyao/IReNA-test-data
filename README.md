# IReNA test data
## scRNA-seq folder:
scRNA-seq test data

**seurat_object.rds**: seurat object, use readRDS() to load it

**Kmeans_clustering_ENS.txt**: consequence of add_ENSID() function

**regulatory_relationships**: consequence of get_cor() function

**filtered_regulatory_relationships.txt**: consequence of filter_regulatory() function in Part2 of IReNA


## bulk RNA-seq folder:
bulk RNA-seq test data

**test_data_RNA-seq.txt**: raw counts of bulk RNA-seq

## ATAC-seq folder
bam file of each sample, differential peaks file of all samples, footprints file of all samples

**sample1_overlapped.bam, sample2_overlapped.bam, sample3_overlapped.bam**: Bam filtered through Footprints

**differential_peaks.bed**：differential peaks generated in step8 of [ATAC-seq pipline](https://github.com/jiang-junyao/ATAC-seq-pipline)

**footprints.bed**: footprints file generated in step10 of [ATAC-seq pipline](https://github.com/jiang-junyao/ATAC-seq-pipline)
