# fake-news-detector
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ishani646/fake-news-detector/blob/main/news-detector.ipynb)
# Fake News Detector — BERT AI

A deep learning project that detects fake news using BERT 
(Bidirectional Encoder Representations from Transformers).

## Model
- Architecture: BERT-base-uncased (Google)
- Parameters: 109,483,778
- Pre-trained on: Wikipedia + BookCorpus
- Fine-tuned on: 44,898 real and fake news articles
- Final accuracy: 100%

## Tech Stack
- Python
- HuggingFace Transformers
- PyTorch
- Gradio (UI)
- Google Colab (GPU training)

## How to Run
1. Open the `.ipynb` file in Google Colab
2. Run all cells in order
3. Use the Gradio UI to test headlines

## Dataset
Fake and Real News Dataset — Kaggle
