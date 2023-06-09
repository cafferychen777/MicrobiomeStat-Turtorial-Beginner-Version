---
description: >-
  Find out how MicrobiomeStat measures up against other leading microbiome
  analysis tools.
---

# How Does MicrobiomeStat Measure Up? A Longitudinal Package Comparison 📊🔍⚖️

### Comparative Table 1: Longitudinal Packages

#### Supported Data Input Formats

|     Package     |                                     Supported Formats                                    |
| :-------------: | :--------------------------------------------------------------------------------------: |
|  MicrobiomeStat | QIIME2, DADA2, BIOM, Mothur, Phyloseq, DGEList, DESeqDataSet, SummarizedExperiment, etc. |
| q2-longitudinal |                                          QIIME2                                          |
|   SplinectomeR  |         Custom format (No other formats import or conversion functions provided)         |
| coda4microbiome |         Custom format (No other formats import or conversion functions provided)         |

#### Alpha Diversity Analysis

|       Package       |                         Supported Metrics                        | Support for Paired Samples | Subgroup Analysis at Different Time Points |
| :-----------------: | :--------------------------------------------------------------: | :------------------------: | :----------------------------------------: |
|  **MicrobiomeStat** | **Shannon, Simpson, Observed Species, Chao1, ACE, Pielou, etc.** |             ✔️             |                     ✔️                     |
| **q2-longitudinal** |           **Metrics need to be calculated externally**           |             ✔️             |                      ❌                     |
|   **SplinectomeR**  |           **Metrics need to be calculated externally**           |              ❌             |                      ❌                     |
| **coda4microbiome** |           **Does not support alpha diversity analysis**          |              ❌             |                      ❌                     |

#### Beta Diversity Analysis

<table data-card-size="large" data-view="cards"><thead><tr><th align="center">Package</th><th align="center">Supported Metrics</th><th align="center">Support for Paired Samples</th><th align="center">Subgroup Analysis at Different Time Points</th><th align="center">Support for Axis Analysis after Ordination</th></tr></thead><tbody><tr><td align="center"><strong>MicrobiomeStat</strong></td><td align="center"><strong>Bray-Curtis (BC), Jaccard, Unweighted UniFrac, Generalized UniFrac, Weighted UniFrac, Jensen-Shannon Divergence, etc.</strong></td><td align="center">✔️</td><td align="center">✔️</td><td align="center">✔️</td></tr><tr><td align="center"><strong>q2-longitudinal</strong></td><td align="center"><strong>Distances need to be calculated externally</strong></td><td align="center">✔️</td><td align="center">❌</td><td align="center">❌</td></tr><tr><td align="center"><strong>SplinectomeR</strong></td><td align="center"><strong>Does not support beta diversity analysis</strong></td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td></tr><tr><td align="center"><strong>coda4microbiome</strong></td><td align="center"><strong>Does not support beta diversity analysis</strong></td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td></tr></tbody></table>

#### Taxa Analysis

<table data-card-size="large" data-view="cards"><thead><tr><th align="center">Package</th><th align="center">Key Features Identification</th><th align="center">Diff. Prevalence</th><th align="center">Paired Samples Support</th><th align="center">Time Points Subgroup Analysis</th><th align="center">Similar Abundance Pattern</th><th align="center">Similar Change Pattern</th><th align="center">Same Changes in Composition Over Time</th></tr></thead><tbody><tr><td align="center"><strong>MicrobiomeStat</strong></td><td align="center">✔️</td><td align="center">✔️</td><td align="center">✔️</td><td align="center">✔️</td><td align="center">✔️</td><td align="center">✔️</td><td align="center">✔️</td></tr><tr><td align="center"><strong>q2-longitudinal</strong></td><td align="center">✔️</td><td align="center">❌</td><td align="center">✔️</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td></tr><tr><td align="center"><strong>SplinectomeR</strong></td><td align="center">✔️</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td></tr><tr><td align="center"><strong>coda4microbiome</strong></td><td align="center">✔️</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td></tr></tbody></table>

#### Multiple Visualization Styles for Longitudinal Data Analysis

|     Package     |                                   Supported Styles                                   |
| :-------------: | :----------------------------------------------------------------------------------: |
|  MicrobiomeStat | Boxplot, Violinplot, Spaghettiplot, Heatmap, Stacked Barplot, Areaplot, Volcano Plot |
| q2-longitudinal |                                Spaghettiplot, Boxplot                                |
|   SplinectomeR  |                                       Lineplot                                       |
| coda4microbiome |                        Boxplot, Densityplot, Barplot, Lineplot                       |

#### Graph Quality for Publication

|     Package     |      Graph Quality     |
| :-------------: | :--------------------: |
|  MicrobiomeStat |      High Quality      |
| q2-longitudinal |      High Quality      |
|   SplinectomeR  | Not up to the standard |
| coda4microbiome | Not up to the standard |
