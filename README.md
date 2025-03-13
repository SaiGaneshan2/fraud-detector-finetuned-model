# fraud-detector-finetuned-model
Fraud Detection Using DeBERTa-V3
Overview

This project leverages DeBERTa-V3 Base, a state-of-the-art transformer model, to detect fraudulent activity in a dataset of call records. The model has been fine-tuned on a balanced dataset to improve classification accuracy.
Dataset

    The dataset (semi_updated_fraudcall_data.csv) consists of labeled call records(self made dataset).
    Preprocessing steps include handling missing values and balancing the dataset by sampling fraud and normal instances.

Model & Training

    Pretrained Model: microsoft/deberta-v3-base from Hugging Face.
    Tokenizer: AutoTokenizer for text processing.
    Training:
        Data is tokenized and fed into the transformer model.
        The model is fine-tuned on labeled fraud and normal call data.
