# IReNA test data
## scRNA-seq.zip:

**seurat_object.rds**: seurat object, including raw counts and normalized data, you can use readRDS() to load it.

## bulk RNA-seq.zip:

**test_data_RNA-seq.txt**: normalized expression profile of bulk RNA-seq data.

## ATAC-seq.zip:
bam file of each sample, differential peaks file of all samples, footprints file of all samples

**SSC1_filter.bam, SSC2_filter.bam, esc_filter.bam**: bam file generated in step11 of [ATAC-seq pipline](https://github.com/jiang-junyao/ATAC-seq-pipline)

**differential_peaks.bed**：differential peaks generated in step8 of [ATAC-seq pipline](https://github.com/jiang-junyao/ATAC-seq-pipline)

**footprints.bed**: footprints file generated in step10 of [ATAC-seq pipline](https://github.com/jiang-junyao/ATAC-seq-pipline)
