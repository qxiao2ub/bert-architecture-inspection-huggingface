# BERT Architecture Inspection with Hugging Face

This repository provides a concise and reproducible notebook for inspecting the internal architecture of `bert-base-uncased` using the Hugging Face Transformers library and PyTorch.

## Project Overview

The notebook explores the structure of a pretrained BERT model from both a configuration and implementation perspective. It is designed to help readers understand how BERT is organized internally, including its hidden dimensions, layer stack, attention heads, and forward-pass behavior.

## What This Notebook Covers

- Loading the pretrained `bert-base-uncased` model
- Inspecting core model configuration:
  - hidden size
  - number of transformer layers
  - number of attention heads
  - intermediate feed-forward dimension
  - vocabulary size
  - maximum positional embeddings
- Examining the first encoder layer in detail
- Running a sample forward pass on tokenized input text
- Interpreting token outputs and hidden-state tensor shapes

## Key Technical Concepts

- Transformer encoder architecture
- Self-attention in BERT
- Hugging Face `AutoTokenizer` and `AutoModel`
- PyTorch tensor inference
- Model introspection and architectural analysis

## Repository Structure

- `Answer for problem1_bert_architecture.ipynb`  
  Main notebook for inspecting the architecture of BERT

## Requirements

Typical dependencies include:

- Python 3.x
- `transformers`
- `torch`
- `pandas`

Install with:

```bash
pip install transformers torch pandas

Example Output

The notebook reports architectural attributes such as:

hidden size = 768

number of hidden layers = 12

number of attention heads = 12

intermediate size = 3072

vocabulary size = 30522

It also demonstrates a forward pass and prints:

tokenized inputs

hidden-state tensor dimensions

Use Cases

This notebook is useful for:

learning BERT architecture

teaching transformer fundamentals

preparing for NLP or deep learning interviews

understanding Hugging Face model objects

building intuition before fine-tuning transformer models

Skills Demonstrated

Transformer model interpretation

Hugging Face model loading and inspection

PyTorch inference workflow

NLP model architecture analysis

Reproducible notebook-based experimentation

License

This project is intended for educational and research demonstration purposes.
