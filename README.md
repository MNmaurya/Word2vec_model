# Word2Vec (Skip-Gram) from Scratch – Part 1

## Overview 

This repository contains my implementation of the initial stages of the Word2Vec Skip-Gram algorithm using pure Python. 

The goal of this project is to understand how Word2Vec works internally instead of directly using libraries such as Gensim.  

This is Part 1 of the project, covering data preprocessing and training data generation.
 
---

## Dataset

A small custom corpus is used for learning:

```
The king is strong.
The queen is wise.
The prince is young.
```

---

## What I Implemented

- Text preprocessing
- Lowercasing
- Punctuation removal
- Tokenization
- Vocabulary creation
- Word-to-Index mapping
- Sliding Window generation
- Skip-Gram training pair generation
- One-Hot Encoding from scratch

---

## Sample Training Pair

Input:

```
king
```

Output:

```
the
is
```

Training pairs:

```
(king, the)
(king, is)
```

---

## Technologies Used

- Python
- Jupyter Notebook
- Regular Expressions (re)

---

## Current Status

✅ Data preprocessing completed

✅ Skip-Gram dataset generated

✅ One-Hot Encoding implemented

🔄 Next Step:
Implement the neural network, forward propagation, softmax, loss calculation, backpropagation, and train Word2Vec embeddings from scratch.

---

## Learning Objective

This project focuses on understanding the complete working of the Word2Vec Skip-Gram architecture instead of treating it as a black-box library.
