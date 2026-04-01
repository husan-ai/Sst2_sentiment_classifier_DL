Sentiment Analysis with DistilBERT (SST-2)

This project implements a sentiment classification model using DistilBERT fine-tuned on the SST-2 dataset.

Overview

The model classifies text into:

Positive (1)
Negative (0)

We use a smaller subset of the dataset for faster training:

Train: 2000 samples
Test: 400 samples
Technologies
Python
Hugging Face Transformers
Datasets
PyTorch
Workflow
Load SST-2 dataset
Preprocess and tokenize text
Fine-tune DistilBERT model
Evaluate model performance
Run predictions on new text
Example
text = "This movie was amazing!"
# Output: Positive
Result

The model is evaluated using accuracy metric on the validation set.

Note

This project is a simple NLP pipeline for learning and demonstration purposes.
