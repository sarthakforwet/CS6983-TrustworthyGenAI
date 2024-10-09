# CS 4973 / CS 6983 Homework 1
This repository contains code and resources for Homework 1 of CS 4973 / CS 6983 (Fall 2024) taught by Instructor **Alina Oprea**.

## Assignment Overview
This assignment focuses on working with and evaluating various language models, including:
- Comparing multiple GPT-2 models using perplexity metrics
- Generating text using different decoding strategies
- Fine-tuning BERT for sentiment classification

## Setup
- Clone this repository
- Install required dependencies:

```{bash}
pip install -r requirements.txt
```

Download the datasets from the provided Google Drive link

Find the problems in more detail in the `HW1.pdf` file. Below is a slight overview of each problem.

**Problem 1: Comparing multiple LLMs:** Evaluates GPT-2 small, medium, and large models on the wikitext dataset. Computes and visualizes perplexity metrics

**Problem 2: Generating text with LLMs** Implements greedy decoding, top-k sampling, and beam search for text generation. Computes **MAUVE scores** to compare generated text with ground truth

**Problem 3: Fine-tuning BERT for sentiment classification** Fine-tunes **DistilBERT** on **IMDB reviews dataset**. Compares performance of fine-tuning last layer vs. all layers

For solutions to the problems, refer to the notebook provided in the repository.
