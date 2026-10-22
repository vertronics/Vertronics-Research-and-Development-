# Predictive Maintenance Research

## Overview

This project investigates the use of unsupervised machine learning to identify operating-condition patterns in the AI4I 2020 Predictive Maintenance Dataset.

The study applies K-Means clustering to machine operating data, evaluates cluster quality, and examines associations between discovered clusters and recorded machine failures.

## Research Objectives

- Apply K-Means clustering to continuous equipment operating variables.
- Evaluate clustering quality using statistical metrics.
- Examine associations between cluster membership and recorded failure labels without using those labels as clustering inputs.
- Assess practical applications, limitations, and opportunities for further research.

## Methodology

The analysis includes data inspection, feature preparation, standardization, K-Means clustering, cluster evaluation, and post-hoc statistical analysis of failure patterns.

The primary clustering analysis uses five continuous operating-condition variables:

- Air temperature
- Process temperature
- Rotational speed
- Torque
- Tool wear

Product type is excluded from the primary clustering features to reduce the risk of clusters simply reflecting product categories. Failure labels are used for post-hoc analysis, not as clustering inputs.

## Key Findings

- The selected three-cluster solution showed modest separation between operating-condition groups.
- Cluster assignments were highly stable across the tested random seeds under the same preprocessing procedure.
- Failure rates differed across clusters, with a statistically significant association between cluster membership and recorded failures.
- The observed association had a small effect size and does not establish causation or demonstrate a validated predictive-maintenance system.
- Cluster assignments were sensitive to feature scaling, supporting the use of standardized features for the primary analysis.

Refer to the research report and notebook for detailed metrics, visualizations, and limitations.

## Research Materials

- **[Research Report (PDF)](paper/Vertex_Electronics_Predictive_Maintenance_Analysis.pdf)** — published technical report.
- **[Research Notebook](notebooks/predictive_maintenance_clustering.ipynb)** — computational analysis, clustering procedure, evaluation metrics, and results.
- **[Notebook Documentation](notebooks/README.md)** — information about the research notebook.
- **[Dataset Documentation](data/README.md)** — dataset source, structure, attribution, and licensing.
- **[Research Results](results/README.md)** — documentation for quantitative outputs.
- **[Research Figures](figures/README.md)** — documentation for visualizations.

## Dataset

The study uses the [AI4I 2020 Predictive Maintenance Dataset](https://archive.ics.uci.edu/dataset/601/ai4i+2020+predictive+maintenance+dataset) from the UCI Machine Learning Repository.

The dataset is synthetic and contains 10,000 records and 14 columns. The raw dataset is not included in this repository. See the dataset documentation for access and attribution guidance.

## Reproducibility

The research notebook documents the computational analysis. To reproduce the study, obtain the dataset from its original source, place it at the location expected by the notebook, install the required Python libraries, and execute the notebook.

The numerical results and figures should be checked against the notebook before being published as separate files.

## Scope and Limitations

This is an exploratory study using synthetic data. The clustering results identify operating-condition groupings and associations with recorded failures; they do not independently establish predictive accuracy, causal relationships, or real-world industrial performance.

Further research is required to evaluate generalization to real industrial data and determine whether the identified patterns can support operational maintenance decisions.

## Licensing

The research report is intended to be shared under the Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0) licence, subject to the notice in the published report.

The dataset and other third-party materials remain subject to their respective licences. The notebook and other original code may require separate licensing terms.

## Author

**Taylor Ng'andwe**  
Vertex Electronics

## Status

The initial clustering analysis and research report are available. Further validation, publication of verified outputs, and extensions remain possible.
