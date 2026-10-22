# Predictive Maintenance Through Unsupervised Clustering

This research project by **Vertex Electronics** investigates operating-condition patterns in the AI4I 2020 Predictive Maintenance Dataset using K-Means clustering.

The study examines whether groups of operating conditions identified through unsupervised learning are associated with differences in recorded machine-failure rates.

## Research Objectives

- Identify operating-condition groups using K-Means clustering.
- Evaluate clustering quality across different numbers of clusters.
- Compare operating characteristics and recorded failure rates across the resulting clusters.
- Discuss the findings, limitations, and potential relevance to predictive maintenance research.

## Methodology

The primary clustering analysis uses five continuous variables:

- Air temperature
- Process temperature
- Rotational speed
- Torque
- Tool wear

Product type is excluded from the primary clustering features. Recorded failure labels are used after clustering to examine associations between cluster membership and machine failures.

## Key Findings

- The three-cluster solution provides a useful segmentation of the operating-condition data among the tested cluster counts.
- The clusters differ in their operating profiles and observed failure rates.
- The observed associations do not establish causation.
- The analysis is exploratory and does not demonstrate a validated industrial predictive-maintenance system.
- Clustering outcomes can be sensitive to feature scaling and analytical choices.

## Research Materials

| Resource | Description |
|---|---|
| [Research report](paper/Vertex_Electronics_Predictive_Maintenance_Analysis.pdf) | PDF report presenting the study |
| [Analysis notebook](notebooks/predictive_maintenance_clustering.ipynb) | Computational workflow and clustering analysis |
| [Research figures](figures/) | Visualizations generated for the study |
| [Quantitative results](results/) | CSV files containing evaluation metrics and cluster comparisons |
| [Dataset information](data/README.md) | Dataset source, access instructions, and attribution |

## Reproducibility

The analysis notebook and accompanying CSV files and figures provide the main research materials. The dataset is not included in this repository and must be obtained separately. Consult the [data README](data/README.md) for its source and attribution information.

When reproducing the analysis, use the dataset filename and location expected by the notebook and install the required Python dependencies.

## Limitations

The AI4I 2020 dataset is synthetic. The results should not be interpreted as evidence of real-world industrial performance, causal relationships, or a deployable failure-prediction system. Further validation on appropriate real-world data would be required before practical deployment.

## Licensing and Attribution

The research report is intended to be shared under the **Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0)** licence, subject to the notice accompanying the PDF.

The dataset and any third-party materials remain subject to their respective licences. See the [data README](data/README.md) for dataset attribution and the [paper README](paper/README.md) for report licensing information.

## Research Organisation

This study forms part of the research and development activities of **Vertex Electronics**.
