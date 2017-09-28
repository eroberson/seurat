# News
All notable changes to Seurat will be documented in this file.
The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)

## [In develop]
### Added
- Support for using MAST, DESeq2, and zingeR packages for differential expression testing in FindMarkers

### Changed
- Default DE test changed to Wilcoxon rank sum test

## [2.0.1] - 2017-08-18
### Added
 - Now available on CRAN
 - Updated documentation complete with examples
 - Example datasets: `pbmc_small` and `cc.genes`
 - C++ implementation for parts of FindVariableGenes

## [2.0.0] - 2017-07-26
### Added
- New method for aligning scRNA-seq datasets
- Significant code restructuring 
- New methods for scoring gene expression and cell-cycle phases
- New visualization features (do.hover, do.identify)