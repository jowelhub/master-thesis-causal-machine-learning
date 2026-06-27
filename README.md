# Causal Machine Learning for Markdown Price Optimization in Retail

This repository contains the code, LaTeX files, outputs, and the compiled report for the Master's Thesis: **"Causal Machine Learning for Markdown Price Optimization in Retail"** (MSc in Fundamentals of Data Science, Universitat de Barcelona, in collaboration with Mango).

## Repository Structure

The files and folders are organized as follows:

```text
├── latex/                          # LaTeX source files for compiling the thesis
├── thesis_outputs/                 # Saved visual and numerical results (plots and tables)
├── master_thesis_notebook.ipynb    # Clean Jupyter notebook containing the modeling workflow
├── master_thesis.pdf               # Compiled PDF version of the Master's Thesis report
└── README.md                       # Repository documentation
```

## Data Privacy & Confidentiality

Because this project was developed in collaboration with Mango, the historical sales, stock, and pricing datasets are proprietary. For this reason, **the raw datasets are not included in this public repository.**

To ensure transparency and allow for review of the methodology, the main notebook (`master_thesis_notebook.ipynb`) is provided in a **fully executed state**. This preserves all inline calculations, intermediate outputs, and diagnostic plots so that the modeling workflow remains verifiable. Additionally, the generated results are archived in the `thesis_outputs/` directory.

## Production vs. Public Thesis Implementations

This public repository serves as the **academic-facing version** of the research, focusing on the underlying methodology, CATE estimation, and curve-quality evaluation. 

In parallel, an operational version of this causal machine learning framework was developed for Mango’s internal codebase. That system is written using modular Python classes and runs automated pipelines orchestrated via **Apache Airflow DAGs on Databricks clusters**. Because it contains proprietary infrastructure, data access layers, and deployment logic, that codebase remains strictly private.