# Text Classification Using Embeddings for Luganda Text Corpus

This repository contains code for a text classification experiment using embeddings for the Luganda text corpus. In this experiment, we utilized Support Vector Machine (SVM) as the classification model and performed hyper-parameter tuning to optimize its performance. Due to limitations imposed by the Cohere API for free users, the dataset was sampled to 500 samples for training and evaluation purposes.

## Experiment Details
- **Model:** Support Vector Machine (SVM)
- **Data:** Luganda Text Corpus
- **Data Size:** 500 samples (due to API limitations)
- **Embeddings:** Utilized embeddings for text representation
- **Validation Accuracy:** 45.6%

## Experiment Process
1. **Data Sampling:** Due to limitations in the Cohere API for free users, the Luganda text corpus was sampled to 500 data points for the experiment.

2. **Text Embeddings:** Text data was converted into embeddings to enable numerical representation for the SVM model. Embeddings play a crucial role in capturing semantic meanings of words and phrases, enhancing the model's understanding of the text.

3. **Model Selection:** SVM was chosen as the classification model due to its effectiveness in text classification tasks and its ability to handle high-dimensional data like embeddings.

4. **Hyper-parameter Tuning:** Hyper-parameter tuning was performed to optimize the SVM model's performance. Various hyper-parameters such as C, kernel type, and gamma were tuned to achieve the best results.

5. **Training and Evaluation:** The model was trained on the sampled dataset and evaluated using validation data. The validation accuracy obtained was 45.6%, indicating the model's ability to correctly classify Luganda text samples.
