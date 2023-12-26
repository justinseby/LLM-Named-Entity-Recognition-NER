
## MultiNERD Named Entity Recognition (NER) Project Overview

This project focuses on training and evaluating a Named Entity Recognition (NER) model for English using the MultiNERD dataset. The goal is to develop two systems (System A and System B) by fine-tuning a pre-trained language model on the English subset of the dataset, filtering out non-English examples, and predicting five entity types (PERSON, ORGANIZATION, LOCATION, DISEASES, ANIMAL) along with the 'O' tag.

## Notebooks Explanation

### 1. Dataset_Exploration_(EDA).ipynb

- **Objective:**
  - Explore the MultiNERD dataset and gain insights into its structure and characteristics.
  - Understand the distribution of entity types and relevant patterns.

### 2. SystemA_RISE.ipynb

- **Objective:**
  - Fine-tune a pre-trained language model on the English subset of the training set (System A).
  - Evaluate the model's performance on relevant metrics.

### 3. SystemB_RISE.ipynb

- **Objective:**
  - Modify the dataset to predict five entity types (PERSON, ORGANIZATION, LOCATION, DISEASES, ANIMAL) and the 'O' tag.
  - Fine-tune the model on the filtered dataset (System B).
  - Evaluate the performance of System B.


## Instructions to Run the Notebooks



## Evaluation Metrics

### System A

#### Training Metrics

| Epoch | Training Loss | Validation Loss | Precision | Recall | F1 | Accuracy |
|-------|----------------|------------------|-----------|--------|----|----------|
| 1     | -              | -                | -         | -      | -  | -        |
| 2     | -              | -                | -         | -      | -  | -        |

#### Test Set Metrics

| Metric   | Value      |
|----------|------------|
| Accuracy | -          |
| Precision| -          |
| Recall   | -          |
| F1       | -          |

### System B

#### Training Metrics

| Epoch | Training Loss | Validation Loss | Precision | Recall | F1 | Accuracy |
|-------|----------------|------------------|-----------|--------|----|----------|
| 1     | -              | -                | -         | -      | -  | -        |
| 2     | -              | -                | -         | -      | -  | -        |

#### Test Set Metrics

| Metric   | Value      |
|----------|------------|
| Accuracy | -          |
| Precision| -          |
| Recall   | -          |
| F1       | -          |

---

This template provides a structure for presenting the training and test set metrics for both System A and System B. Replace the placeholders with the actual values when you have the results.
## Additional Resources
