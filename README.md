# PropiCellProfiler
CellProfiler-based pipeline that enables automated segmentation of cells within the lamina propria of colonic tissue samples.

This project provides two CellProfiler-based segmentation pipelines for histological analysis of immunostained, confocal images of intestinal tissue. One pipeline is tailored for epithelial cell segmentation (EpiCellProfiler), while the other focuses on lamina propria cells (immune-cell-rich regions, PropiCellProfiler). Both pipelines enable automated single-cell analysis, protein quantification of any targets of interest, and export of results for downstream statistical evaluation.

Main Features

1. Automated segmentation optimized for distinct intestinal compartments (epithelium vs. lamina propria).
2. Quantification of protein markers (e.g., G3BP1) at the single-cell level.
3. Extraction of nuclear morphology and cellular signal intensities.
4. Export of tabular single-cell data for downstream analysis in R or Python.

Usage

1.	Select the appropriate pipeline (EpiCellProfiler or PropiCellProfiler).
2.	Download and install CellProfiler
3.	Open the pipeline in CellProfiler.
4.	Load your image data into the Images module or test with the provided sample images.
5.	Run the pipeline and export results.


NOTE: This pipeline was explicitly designed for intestinal tissue, but we have observed that it is also applicable to other human tissues.
For more detailed information, please refer to our forthcoming research article: [link to paper]
