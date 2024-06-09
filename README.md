# Diurnal-Transcriptome-Analysis

This repository contains R scripts for analyzing diurnal transcriptome data from baboons, focusing on cardiac ion channel genes. The analysis includes data preprocessing, calculation of baseline expression, percentage difference from baseline, and rhythmicity analysis using MetaCycle.

Overview

1. Data Acquisition and Preprocessing: Downloading and preprocessing FPKM normalized expression 
   data and metadata from GEO.
2. Selection of Heart Tissue and Cardiac Ion Channel Genes: Filtering for heart tissue samples and 
   specific cardiac ion channel genes.
3. Calculation of Baseline Expression and Percentage Difference: Computing baseline expression and 
   percentage difference for each gene.
4. MetaCycle Analysis: Identifying rhythmic genes using the MetaCycle package.
5. Visualization: Creating bar plots of percentage difference from baseline with standard 
   deviations across different Zeitgeber Times (ZT).
