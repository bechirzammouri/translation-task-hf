# T5 Translation: English to French 

This repository contains a notebook that fine-tunes a T5 model for English-to-French translation using Hugging Face libraries. It is part of a practical exercise from the official [Hugging Face LLM Course]([https://huggingface.co/course](https://huggingface.co/learn/llm-course/chapter1/1?fw=pt)).

##  Task Overview

The objective of this project is to fine-tune a pre-trained T5 Transformer model (`google-t5/t5-small`) on a translation dataset to learn how to translate English text into French.

This work was completed as an exercise from the Hugging Face Course, under the chapter on **Transforemers models**. 

## 🛠 Tools & Libraries Used

- 🤗 [Transformers](https://huggingface.co/docs/transformers/fr/index)
- 🤗 [Datasets](https://huggingface.co/docs/datasets/index)
- Evaluate
- Tokenizers
- Jupyter Notebook

##  How to Run

1. Clone the repository:

```bash
gh repo clone bechirzammouri/translation-task-hf
```
2. Install dependencies
```bash
pip install transformers datasets evaluate
```
## What’s Inside
- Preprocessing and tokenizing translation pairs
- Fine-tuning google-t5/t5-small using Hugging Face Seq2SeqTrainer
- Evaluating model performance using BLEU score
- Running predictions and saving the model

