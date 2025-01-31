# Network Science and Graph Learning Homework

This repository contains the code and analysis for the **Network Science and Graph Learning** homework assignment. The project focuses on analyzing the **Facebook100 dataset**, which consists of friendship networks from 100 U.S. universities in 2005. The goal is to explore various network properties, perform community detection, and evaluate link prediction algorithms.

---

## Table of Contents
1. [Dataset](#dataset)
2. [Questions and Tasks](#questions-and-tasks)

---

## Dataset

The **Facebook100 dataset** contains anonymized friendship networks from 100 U.S. universities, captured in September 2005. Each network includes nodes (users) and edges (friendships), along with user attributes such as:
- **Status**: Undergraduate, graduate student, faculty, staff, alumni.
- **Dorm**: Residence hall (if applicable).
- **Major**: Academic major (if applicable).
- **Gender**: Male (M) or Female (F).
- **Graduation Year**: Year of graduation.

The dataset is available in the following GitHub repository:  
[Facebook100 Dataset](https://classroom.github.com/a/jm4seIEs)

---

## Questions and Tasks

The homework assignment consists of the following questions:

### Question 1: Reading
- Read and summarize the provided research papers on the Facebook100 dataset and social network analysis.

### Question 2: Social Network Analysis
- Analyze three networks (Caltech, MIT, Johns Hopkins) from the Facebook100 dataset:
  - Plot degree distributions.
  - Compute global and local clustering coefficients.
  - Calculate edge density and discuss graph sparsity.
  - Draw scatter plots of degree vs. local clustering coefficient.

### Question 3: Assortativity Analysis
- Investigate assortativity patterns for five vertex attributes:
  - Student/faculty status, major, vertex degree, dorm, gender.
  - Create scatter plots and histograms of assortativity values.

### Question 4: Link Prediction
- Implement and evaluate link prediction metrics:
  - Common Neighbors, Jaccard Coefficient, Adamic/Adar Index.
  - Evaluate the performance of these metrics using precision, recall, and top-k accuracy.

### Question 5: Label Propagation
- Implement the label propagation algorithm to recover missing node attributes (dorm, major, gender).
- Evaluate the algorithm's accuracy for different fractions of missing data.

### Question 6: Community Detection
- Formulate a research question about group formation in the Facebook100 dataset.
- Use community detection algorithms to validate your hypothesis.
- Compare results across different universities.

---
