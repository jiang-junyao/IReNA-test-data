# [IReNA](https://github.com/jiang-junyao/IReNA) test data
## scRNA-seq.zip:

**seurat_object.rds**: seurat object, including raw counts and normalized data, you can use readRDS() to load it.

## bulk RNA-seq.zip:

**test_data_RNA-seq.txt**: normalized expression profile of bulk RNA-seq data.

## ATAC-seq.zip:
bam file of each sample, differential peaks file of all samples, footprints file of all samples

**SSC1_filter.bam, SSC2_filter.bam, esc_filter.bam**: filtered bam file generated in part3 of IReNA. Because the size of original bam file is too large, so we upload filtered bam file here.

**differential_peaks.bed**：differential peaks generated in step8 of [ATAC-seq preprocessing pipline](https://jiang-junyao.github.io/IReNA/ATAC-seq-preprocessing)

**footprints.bed**: footprints file generated in step10 of [ATAC-seq preprocessing pipline](https://jiang-junyao.github.io/IReNA/ATAC-seq-preprocessing)
