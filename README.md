# mlops-assignment2-hf-wandb

## Project Description
This project demonstrates an end-to-end MLOps workflow using Hugging Face Transformers, Weights & Biases, Kaggle GPU training, and Hugging Face Hub deployment.

DistilBERT was fine-tuned on Goodreads review classification.

---

## Training Platform
Kaggle GPU Notebook

---

## Results

| Metric | Score |
|---|---|
| Accuracy | 0.571 |
| F1 Score | 0.574 |
| Eval Loss | 2.36 |

---

## Links

- Kaggle Notebook: https://www.kaggle.com/code/sonalkmr/mlops-assignment-2-fine-tuning-classification
- Hugging Face Model: https://huggingface.co/sonalkmr/distilbert-goodreads-genres
- W&B Dashboard: https://wandb.ai/sonalkmr795-ltimindtree/mlops-assignment2/runs/m1kkqv28?nw=nwusersonalkmr795

---

## Technologies Used

- Hugging Face Transformers
- DistilBERT
- Weights & Biases (W&B)
- Kaggle GPU
- PyTorch
- Scikit-learn

---

## Setup

```bash
pip install -r requirements.txt
```

---

## Workflow

1. Data preprocessing
2. Tokenization using DistilBERT tokenizer
3. Fine-tuning DistilBERT model
4. Experiment tracking with W&B
5. Evaluation using Accuracy and F1 Score
6. Model deployment to Hugging Face Hub
