# AA-identify

A machine learning model that identifies amino acid from copper(II)-functionalized MspA nanopore signals.

Zhang, M., Tang, C., Wang, Z. et al. Real-time detection of 20 amino acids and discrimination of pathologically relevant peptides with functionalized nanopore. Nat Methods (2024). https://doi.org/10.1038/s41592-024-02208-7

This repo recreates the machine learning model that was created in the article above. 

## Assumptions 
- In the paper, they tested several machine learning models. For the purposes of this project, I will only be recreating the best model (Random Forest model) and comparing outputs
- I0 was used to normalize the signal received from the nanopore machine. It is unclear what I0 is. For this project I0 will assume to be equal to 1. More information in Supplementary figure 8.



