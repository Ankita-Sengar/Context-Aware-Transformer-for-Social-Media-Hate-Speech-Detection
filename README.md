# Context-Aware-Transformer-for-Social-Media-Hate-Speech-Detection
Domain-adapted transformer using pretraining and fine-tuning on multilingual social media datasets


This project uses RoBERTa and DistilBERT for detecting hate speech in social media content using fine-tuned transformer models.

## Highlights
- Models: distilroberta-base, roberta-base
- Tokenizer: HuggingFace
- Framework: PyTorch + Trainer API
- Metrics: Accuracy, F1, Precision, Recall

## Run
```bash
pip install -r requirements.txt
python train.py
