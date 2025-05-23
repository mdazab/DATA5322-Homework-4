# Practical Homework 4: Unsupervised Learning

# Hofidar Cost Center Analysis

This project applies unsupervised learning techniques to analyze financial and operational data from Washington State hospitals. The dataset includes information on salaries, staffing, revenue, expenses, facility size, and service volumes for hospital cost centers across multiple institutions and years.

Our goal is to uncover structure in hospital spending patterns and operational practices using PCA, matrix completion, and clustering.

---

## Objective

To identify natural groupings of hospital cost centers and understand the driving factors behind operational and financial differences — without relying on labeled outcomes.

---

## Methods Used

- **Principal Component Analysis (PCA)** and **Singular Value Decomposition (SVD)**  
  To reduce dimensionality and visualize key variance in the dataset.

- **Matrix Completion**  
  To assess the model's ability to reconstruct missing financial values from incomplete records.

- **K-Means Clustering**  
  To discover cost center groupings with similar spending profiles.

- **Hierarchical Clustering**  
  To build a dendrogram and explore nested structures using various linkage methods.

---

## Key Questions

- Which features drive the most variation in hospital cost centers?
- Can we identify meaningful clusters of departments based on cost profiles?
- What patterns emerge when visualizing hospitals in PCA space?
- How well can missing values in hospital records be recovered?

---

## Repository Structure
