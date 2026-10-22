# Research Results

This directory contains quantitative results from the Vertex Electronics predictive maintenance study using the AI4I 2020 Predictive Maintenance Dataset.

## Published Results

| File | Description |
|---|---|
| [`cluster_evaluation_metrics.csv`](cluster_evaluation_metrics.csv) | K-Means clustering evaluation metrics for candidate cluster counts |
| [`cluster_operating_means.csv`](cluster_operating_means.csv) | Mean operating-condition measurements for each cluster |
| [`failure_rates_by_cluster.csv`](failure_rates_by_cluster.csv) | Recorded machine-failure counts and observed failure rates by cluster |
| [`failure_rates_by_product_type.csv`](failure_rates_by_product_type.csv) | Observed failure rates by product type within each cluster |

## Interpretation

The results describe patterns identified through exploratory clustering. Cluster membership is associated with differences in observed failure rates, but these findings do not establish causation or demonstrate a validated predictive-maintenance system.

The results should be interpreted alongside the analysis notebook and the research report.

## Reproducibility

The accompanying analysis is available in [`predictive_maintenance_clustering.ipynb`](../notebooks/predictive_maintenance_clustering.ipynb). The dataset must be obtained separately; see the [`data README`](../data/README.md) for its source and attribution information.

These CSV files are research outputs and should be checked against the notebook when the analysis is updated.
