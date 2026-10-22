# Research Notebooks

This directory contains the Jupyter notebook used for the Vertex Electronics predictive maintenance clustering study.

## Available Notebook

- [`predictive_maintenance_clustering.ipynb`](predictive_maintenance_clustering.ipynb) — analysis of operating-condition patterns in the AI4I 2020 Predictive Maintenance Dataset using K-Means clustering.

The notebook contains the computational workflow for clustering, evaluation, and analysis of the relationship between cluster membership and recorded machine failures.

## Dataset Setup

The raw dataset is not included in this repository. Obtain it from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/601/ai4i+2020+predictive+maintenance+dataset).

Place the dataset CSV file in the [`data`](../data/) directory and name it `ai4i2020.csv`.

Expected path relative to the repository root:

`predictive-maintenance/data/ai4i2020.csv`

See the [dataset README](../data/README.md) for source information, attribution, and licensing details.

## Reproducibility

Open `predictive_maintenance_clustering.ipynb` in Jupyter and run the cells in order. Ensure that the required Python libraries are installed and that the dataset is available at the expected path.

For the study's findings and limitations, consult the [project README](../README.md) and the [research report](../paper/Vertex_Electronics_Predictive_Maintenance_Analysis.pdf).
