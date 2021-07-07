#  Analysis of rhodamine diffusion in microfluidic channels

[Jupyter notebook](absorption_analysis.ipynb) used for extracting and analyzing diffusion profiles from fluorescence images recorded at various timepoints for different materials/ dyes.
Extracted profiles are used to compose Fig. 3 in [Schneider et al. (2021)](https://doi.org/10.3390/mi12050575).

### Purpose
Extract, average and compare 1D-profiles from 2D-images recorded at different days. 

### Input
Fluorescence images for various conditions at defined timepoints.

Sample images indicating diffusion between two timepoints:
![sample_profile](/figs/sample_profile.png)

### Output
Analysis in notebook produces following output profiles:
![Rh101_combined](/figs/Rh101_combined_mean.png)
![Rh6G_combined](/figs/Rh6G_combined_mean.png)
![RhB_combined](/figs/RhB_combined_mean.png)

## Citation
Please cite **S. Schneider, E. J. S. Brás, O. Schneider, K. Schlünder, and P. Loskill, [Facile Patterning of Thermoplastic Elastomers and Robust Bonding to Glass and Thermoplastics for Microfluidic Cell Culture and Organ-on-Chip ](https://doi.org/10.3390/mi12050575), Micromachines 12, 575 (2021)** if you reuse some of the code for your own analysis.