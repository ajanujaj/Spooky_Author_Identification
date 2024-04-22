# Spooky Author Identification

## Dataset
[Spooky Author Identification Competition Dataset](https://www.kaggle.com/competitions/spooky-author-identification)

## Requirments
1. Pandas
2. numpy
3. matplotlib
4. sklearn
5. transformers
6. torch
7. seaborn
8. collection

## Implementation Justification

In this project, I aimed to develop a Natural Language Processing (NLP) model to identify authors based on their written text. I experimented with two distinct approaches:

1. **Logistic Regression Model**:
   - **Justification**: Logistic regression is a simple yet effective baseline model for binary classification tasks like author identification. It provides interpretable results and can serve as a benchmark for more complex models.
   - **Advantages**: 
     - Computationally efficient, especially for large datasets.
     - Offers probabilistic interpretations of predictions.
   - **Limitations**:
     - Assumes linear relationship between features and target variable, which may not hold true for highly non-linear data.
     - Limited capacity to capture complex patterns in text data compared to deep learning models.

2. **BERT Model**:
   - **Justification**: BERT (Bidirectional Encoder Representations from Transformers) has demonstrated state-of-the-art performance across various NLP tasks, including text classification. It excels in capturing contextual information and semantic understanding from text data.
   - **Advantages**:
     - Utilizes pre-training on large text corpora, enabling transfer learning and robust performance on downstream tasks with limited labeled data.
     - Captures bidirectional context information, allowing for more nuanced understanding of text semantics.
   - **Limitations**:
     - High computational and memory requirements during training and inference.
     - Requires substantial computational resources and time for fine-tuning on task-specific data.

By implementing both logistic regression and BERT models, I aimed to compare the performance and trade-offs between a traditional machine learning approach and a state-of-the-art deep learning model in the context of author identification.

## Execution
Run the idetity.ipynb
