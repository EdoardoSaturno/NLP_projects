# Multi-Label Text Classification using Transformer-Based Architectures

This project aims to address **multi-label text classification** using **transformer-based architectures**.

The methodology is based on the academic paper:

> Kiesel et al. (2022). _Identifying the Human Values behind Arguments_. Proceedings of ACL 2022.  
> 📄 [Read the paper](https://aclanthology.org/2022.acl-long.306.pdf)

## Objective

The goal is to replicate and adapt the approach described in the paper to classify text instances with multiple labels corresponding to underlying human values.

## Methodology

- **Transformer Models:** Utilizes models such as BERT, RoBERTa, or similar for encoding arguments.
- **Multi-Label Classification:** Each argument may be associated with multiple human values, requiring the model to handle overlapping label sets.
- **Loss Function & Evaluation:** Binary cross-entropy loss and metrics such as micro/macro F1-score are used to evaluate performance.

## Future Work

- Experiment with different transformer architectures and fine-tuning strategies
- Explore zero-shot or few-shot generalization to new argument domains
- Investigate explainability methods to interpret predicted human values
