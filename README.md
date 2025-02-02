# RAG for Improved LLM Performance on PopQA Dataset

## Overview
This repository contains the code for our research on enhancing Large Language Model performance in open-domain question answering tasks. We focus on the integration of Retrieval-Augmented Generation (RAG) techniques to improve the Llama3-70b-8192 model's ability to effectively process and answer questions from the PopQA dataset.
By comparing baseline performance against two RAG implementations—Naive Retrieval and Reranking Retrieval—we demonstrate how retrieval of contextual information can enhance model accuracy and response relevance.

## Authors
- Marina Fomicheva
- Iuliia Lysova
- German Anashkin

### Notebooks
- **`RAG_LLM_performance_PopQA_dataset.ipynb`**:
  This Jupyter notebook includes data preprocessing, model implementation, evaluation and result visualization.

## Results
Implementing RAG techniques led to substantial improvements in LLM performance:
- **Baseline accuracy**: 32.6%
- **Naive Retrieval accuracy**: 89.6%
- **Reranking Retrieval accuracy**: 91.4%

These results highlight the effectiveness of RAG techniques in improving the accuracy and relevance of responses in open-domain QA tasks.
