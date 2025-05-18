# DEMON-D

Detection of Erroneous or Misannotated sequences in public DNA datasets using deep learning embEDdings and outlier detectioN

Public DNA datasets (like NCBI, ENA, etc.) often contain sequencing or annotation errors, such as mislabeled resistance genes, poorly trimmed reads, or contamination.
This project builds a lightweight ML pipeline that uses pretrained deep embeddings (like DNABERT) + unsupervised anomaly detection to flag potential outliers in labeled DNA sequence datasets.
