# Sexism and Bias in AI Tools: Workplace Empirical Benchmark

This repository contains the code and experimental benchmark for the ISEP Master of Engineering (Business Intelligence major) compensation project on **"Sexism and bias in AI tools"**.

## Project Overview

The project evaluates NLP classification models on detecting sexist statements in professional communication datasets (Grosz & Conde-Cespedes, 2020). We compare:
- A linear baseline: **TF-IDF (1,2-grams) + Logistic Regression**
- A fine-tuned contextual model: **RoBERTa-base**

It also includes a counterfactual fairness audit on gendered sentence pairs to measure lexical bias across architectures.

## Repository Structure

```text
├── _Sexism_and_bias_in_AI_tools_.ipynb
├── Code (by cell)
├── SD_dataset_FINAL.csv
├── figures_report/
└── README.md                            
