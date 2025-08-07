# Emotion Classifier using BERT

This project is an emotion detection model fine-tuned using BERT to classify emotions from text. It can be used in NLP pipelines for tasks such as chatbots, sentiment analysis, and mental health applications.

---

## Demo

Run the notebook directly in Google Colab:  
[Open In Colab](https://colab.research.google.com/github/MuhammadHamzaKashif/emotion-classifier-using-BERT/blob/main/emotion_classifier.ipynb)

---

## Model Information

- **Base Model**: bert-base-uncased
- **Dataset**: Emotion Dataset (via Hugging Face Datasets)
- **Task**: Multi-class classification
- **Frameworks**: PyTorch and HuggingFace Transformers

---

## Results (Sample)

| Metric   | Value  |
| -------- | ------ |
| Accuracy | 90%+   |
| F1-Score | \~0.89 |
| Loss     | Stable |

---

## Features

- Fine-tuned BERT (distilled-bert-uncased) for emotion classification
- Clean Jupyter Notebook for experimentation
- Supports easy reproducibility and model loading
- Logs and metrics compatible with Weights & Biases (wandb)
