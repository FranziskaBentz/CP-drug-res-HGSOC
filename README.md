# CP-drug-res-HGSOC
Supplementary code repository for the manuscript: "Integrated multiomics profiling of adavosertib and paclitaxel drug resistance in ovarian cancer uncovers therapeutic vulnerabilities to overcome chemoresistance" by Raivola and Rantanen et al. (add doi once available)

This repository contains only the cell painting analysis. All other analysis conducted in the study can be found here: (add link)

Imaging data was acquired using an Opera Phenix and preprocessed using the BIAS software (https://single-cell-technologies.com/bias-2/) and CellProfiler (https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-021-04344-9). For more details, see the method section of the original publication. Features extracted using CellProfiler are publicly available here: (link). Analysis was done on > 25000 cells using > 900 morphological features of the cells, nuclei and nucleolei.

Jupyter Notebooks:
- Cell Painting drug resistant HGSOC cell lines.ipynb:
  - Used to compare morphological features in the different doncidionts as well as the neighborhood analysis
  - Used to generate figure panels 2a, 2b, 2d 
- Actin analysis drug resistant HGSOC cell lines.ipynb:
  - Used to analyze and compare the number and length of actin filaments in the different conditions
  - Used to generate figure panel 2c
  
