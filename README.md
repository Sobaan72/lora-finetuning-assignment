# LoRA Fine-Tuning Assignment

This repository contains the implementation of a toy example for applying **LoRA (Low-Rank Adaptation)** on a pre-trained BERT model for sentiment classification using a subset of the IMDB dataset.

The work is part of an academic assignment that explores parameter-efficient fine-tuning techniques for large language models. The goal is to fine-tune only a small portion of the model using LoRA, significantly reducing training cost and memory usage.

## 🔍 What’s Included

- `LoRA_Assignment.ipynb` – Google Colab notebook with complete implementation
- `trainable_params.png` – Screenshot showing the number of parameters trained using LoRA
- `training_log.png` – Screenshot of model training progress
- `lora_sentiment_model.zip` – (Optional) Saved LoRA adapter weights for deployment or reuse
- `README.md` – Project overview and documentation

## 🧠 Task Summary

- Fine-tuned `bert-base-uncased` using LoRA with rank 4
- Used 500 movie reviews from the IMDB dataset for quick training
- Applied LoRA only to attention layers (query/value)
- Evaluated training logs and parameter efficiency
- Completed bonus task: toy LoRA implementation and GitHub submission

## 📊 Tools & Libraries

- Hugging Face `transformers`
- `datasets` for loading IMDB
- `peft` library for LoRA
- Google Colab (for training)

---

