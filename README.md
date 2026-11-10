# Seoul Bicycle Usage, Spatial & Network Analysis

A Computational and Data Science project exploring Seoul public bicycle (Ddareungi) station usage through data integration, feature engineering, clustering and visualization.

## Project materials

| Material | Purpose |
| --- | --- |
| [Project background and feature definitions](Final_project_1.md) | Research question, sources and engineered station-level features |
| [Preprocessing notebook](2024_ver_Final.ipynb) | Data integration and feature preparation |
| [Clustering notebook](Final%20project_2.ipynb) | Clustering and visualization workflow |
| [Additional notebook](Final_project_3.ipynb) | Additional analysis; review notebook contents before reuse |
| [Initial exploration](Final_project_303.ipynb) | Exploratory work |
| [Intermediate progress report](Final%20project_1.5%20blog%20post.md) | Earlier draft describing a 10-cluster result |
| [Later results and reflection](Final_project_Blog%20post_2.md) | Later report describing 12 PCA components and six labeled clusters |
| [Figures](figures/) | Existing visual results |
| [Presentation and visualization archive](https://drive.google.com/drive/folders/1z4XguGuLbg7mIu1o2Av7UpbBZ3_RrjFk) | Drive archive linked in the author's resume; exact correspondence to each notebook is still being checked |

## Approach

The project reports station-level integration of Seoul Open Data Plaza datasets, construction of infrastructure, mobility, temporal, demographic and network features, and exploration using PCA, K-means and explanatory visualizations. The background document describes December 2024 usage data together with station metadata from a later reference date.

## Reproducibility and version notes

This repository preserves existing coursework and reports. Notebook filenames and historical reports have not been rewritten or removed.

- The intermediate report describes 10 clusters, while the later report presents six cluster labels. These are separate reported versions; the final canonical notebook/result pairing still needs verification.
- Reported evaluation metrics have not been independently reproduced in this publishing pass. Classification against cluster-generated labels does not establish an externally validated station taxonomy.
- Raw data and a verified dependency lockfile are not included. Review notebook imports, local file paths and data sources before running. A fresh end-to-end run is not yet verified.
- Use the source definitions and limitations in the reports when interpreting the results; do not treat exploratory labels as validated operational recommendations.

## Data and attribution

Original data source: [Seoul Open Data Plaza](https://data.seoul.go.kr/). Refer to the background document for dataset names. Check dataset-specific redistribution conditions before adding raw files. No additional raw trip data or personal records were uploaded in this organization pass.

This repository was forked from the author's other account, `Junghooncchoi/JunghoonCDSproject.github.io`. The existing notebooks, reports and figures are retained with their Git history. Additional contributors and third-party methods should be credited where applicable.
