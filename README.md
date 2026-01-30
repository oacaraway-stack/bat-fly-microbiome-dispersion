# Bat Fly Microbiome Dispersion and Habitat Fragmentation

## Project Overview
This repository contains code and data used to analyze and answer if habitat fragmentation destabilizes parasite-associated microbiomes, measured as beta-diversity dispersion in bat fly bacterial communities.

## Repository Contents
- `microbiome_dispersion_analysis.html`  
  Jupyter notebook containing all preprocessing, beta-diversity calculations, dispersion analyses, statistical tests, and visualizations.

microbiome_d… (auto-V) - JupyterLab.pdf
Visual representation of analysis notebook with all preprocessing, beta-diversity calculations, dispersion analyses, statistical tests, and visualizations.

- `Metadata.tsv`  
  Sample metadata including host bat species, parasite identity, and habitat fragment assignment.

- `Metadata_filtered.tsv`
  Sample metadata that is filtered to exclude variables not included in analysis
    
- `LandscapeVariables.csv`  
  Landscape-level variables including fragment area and isolation.

## Analysis Summary
The analysis:
1. Processes ASV count data exported from QIIME2
2. Applies CLR transformation to account for compositionality
3. Calculates Aitchison (Euclidean) beta-diversity distances
4. Quantifies microbiome dispersion at the habitat fragment level
5. Tests whether dispersion differs between fragmented and continuous habitats
6. Visualizes results using PCoA and dispersion plots

## Requirements
- Python 3
- pandas, numpy, scipy, matplotlib, seaborn, scikit-learn

## Reproducibility
All analyses are fully reproducible by running the notebook from top to bottom.

