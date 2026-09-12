# Burnout Analysis — Machine Learning & Orange

Academic exploration of occupational burnout data, developed during a Big Data Analytics master’s degree. The repository brings together a Python notebook, an Orange workflow, a dataset and a written project report.

![Scope](https://img.shields.io/badge/Scope-Academic-08111f?style=flat-square)

## Scope

The notebook implements exploratory analysis, linear and logistic regression, PCA and K-means. The Orange workflow connects tree, random forest, Naive Bayes and SVM learners with evaluation widgets. Saved outputs are historical experiment evidence; they do not establish clinical validity or a currently deployed prediction service.

## Technology / Material

Python · pandas · NumPy · Matplotlib · seaborn · scikit-learn · Orange

## Repository guide

- [eBurnout.ipynb](eBurnout.ipynb)
- [Proyecto resuelto en orange eburnout sucuzhanay.ows](Proyecto%20resuelto%20en%20orange%20eburnout%20sucuzhanay.ows)
- [Final proyect eburnout.pdf](Final%20proyect%20eburnout.pdf)
- [eburnout2.csv](eburnout2.csv)

## 🏗️ Analysis flow

```text
Dataset → inspection & visualization → feature preparation
                                  ├─ Python regression / PCA / clustering
                                  └─ Orange model comparison → evaluation
```

## 📊 Evidence and interpretation

The notebook includes train/test splits, confusion matrices and classification reports. Results depend on the selected features, preprocessing and experimental split. This documentation update did not rerun the experiments or validate a numerical performance claim.

The application-side companion is [eBurnout](https://github.com/sukuzhanay/eburnout); the two repositories document different parts of the broader project.

## Getting started / Reproducibility

Open `eBurnout.ipynb` in Jupyter and review the cells before execution. Point `dataset_path` to your local copy of the dataset; the committed notebook uses an author-specific absolute path. Reconnect the data source in Orange before running its workflow. The environment is not pinned, and the notebook uses legacy pandas/scikit-learn APIs, including `error_bad_lines`; a compatible environment or a separate modernization pass is required.

## Author

**Christian Vladimir Sucuzhanay Arévalo**

Data & AI Solutions Architect | AWS Data Architecture | Generative AI & Amazon Bedrock | Big Data | Former University Lecturer

[Entity Home](https://christiansucuzhanay.com/) · [Technical Portfolio](https://sukuzhanay.github.io/) · [LinkedIn](https://www.linkedin.com/in/sucuzhanay) · [AWS Builder](https://builder.aws.com/community/@sucuzhanay) · [GitHub](https://github.com/sukuzhanay)

**Build. Explain. Teach. Share.**
