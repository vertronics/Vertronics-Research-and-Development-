
# Dataset Documentation

## Dataset Used

**AI4I 2020 Predictive Maintenance Dataset**

- **Source:** UCI Machine Learning Repository
- **Dataset page:** https://archive.ics.uci.edu/dataset/601/ai4i+2020+predictive+maintenance+dataset

## Purpose

This dataset contains equipment operating measurements and failure-related information for research into predictive maintenance and industrial machine learning.

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

Obtain the dataset from the UCI Machine Learning Repository using the link above. Review the dataset's current terms and citation guidance before redistribution or reuse.

The raw dataset is not included in this directory.
