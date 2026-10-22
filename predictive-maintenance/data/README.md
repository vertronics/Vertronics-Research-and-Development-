# Dataset Documentation

## Dataset Used

**AI4I 2020 Predictive Maintenance Dataset**

- **Source:** UCI Machine Learning Repository
- **Dataset page:** https://archive.ics.uci.edu/dataset/601/ai4i+2020+predictive+maintenance+dataset
- **DOI:** https://doi.org/10.24432/C5HS5C
- **Dataset licence:** Creative Commons Attribution 4.0 International (CC BY 4.0), as specified by the UCI dataset record.

## Purpose

This dataset contains equipment operating measurements and failure-related information for research into predictive maintenance and industrial machine learning. It is a synthetic dataset designed to represent predictive maintenance scenarios.

## Dataset Structure

The dataset contains 10,000 records and 14 columns, including product type, air and process temperatures, rotational speed, torque, tool wear, machine failure, and failure-mode indicators.

## Use in This Research

The notebook uses five continuous operating-condition variables for the primary K-Means clustering analysis:

- Air temperature
- Process temperature
- Rotational speed
- Torque
- Tool wear

Product type is excluded from the primary clustering features to reduce the risk of clusters simply reflecting product categories. Failure labels are used for post-hoc statistical analysis, not as clustering inputs.

## Data Access and Attribution

Obtain the dataset from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/601/ai4i+2020+predictive+maintenance+dataset).

Please cite the original dataset when using it in research and comply with its CC BY 4.0 licence, including appropriate attribution and identification of any changes made to the dataset.

The dataset's licence applies to the dataset itself. It does not automatically determine the licence for this repository's research paper or notebook.

## Distribution

The raw dataset is not included in this directory. Readers should obtain it from the original UCI source.
