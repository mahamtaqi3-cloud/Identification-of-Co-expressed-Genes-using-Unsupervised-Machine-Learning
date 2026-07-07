# 🧬 Identification of Co-expressed Genes using Unsupervised Machine Learning

### *Unlocking Yeast Metabolic Insights through Machine Learning*

---

## 🚀 Project Overview

This project leverages **unsupervised machine learning** to decode the complex landscape of gene expression in *Saccharomyces cerevisiae*. By implementing a robust bioinformatics pipeline, we transform raw genomic data into distinct, biologically relevant gene modules—revealing the hidden regulatory networks that drive yeast physiology.

---

## 🛠️ The Pipeline

From raw expression data to biological insight, our workflow ensures scientific rigor and reproducibility:

* **Data Preprocessing**: Feature scaling via `StandardScaler` for unbiased expression profiling.


* **Optimal Cluster Selection**: Precise identification of gene modules ($k=3$) using the **Elbow Method**.


* **Dimensionality Reduction**: Using **Principal Component Analysis (PCA)** to visualize and validate cluster separation.


* **Co-expression Mapping**: Hierarchical clustering and **Clustered Heatmaps** to visualize gene modules.


* **Biological Discovery**: Functional validation via **Gene Ontology (GO) Enrichment Analysis** to link gene modules to actual metabolic pathways.



---

## 📊 Visualizing Results

| Feature | Benefit |
| --- | --- |
| **Elbow Plot** | Confirmed the optimal number of gene modules for high-accuracy clustering. |
| **PCA Plot** | Provided a clear, visual separation of distinct gene expression states. |
| **Clustered Heatmap** | Revealed clear "blocks" of co-regulated genes, highlighting coordinated regulatory behavior. |

---

## 🛠️ Tech Stack

This project utilizes a modern bioinformatics toolchain:

* **Language**: Python 3
* **Data Science**: `pandas`, `numpy`, `scipy`

* **Machine Learning**: `scikit-learn` (K-Means, PCA)


* **Visualization**: `seaborn`, `matplotlib`

* **Bioinformatics**: g:Profiler & Saccharomyces Genome Database (SGD)



---

## 🚀 Getting Started

1. **Clone the repository** and install dependencies:
```bash
pip install -r requirements.txt

```


2. **Open the notebook** in Google Colab.
3. **Run the pipeline** to reproduce visualizations and generate your `gene_clusters.csv` mapping file.

---

*Built with precision for bioinformatics excellence.*
