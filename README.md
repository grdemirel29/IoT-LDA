# IoT-LDA
Analyzing Research Trends of the Internet of Things (IoT): A Topic Modeling Approach

This paper analyzes IoT research trends over the past two decades using text-mining and topic modeling

# Supplementary Material for Sentiment Analysis Review
This repository contains supplementary materials for the paper.

## Contents
- [Datasets](datasets/): The datasets generated and/or analyzed during this study.

### Computational Workflow (Orange Data Mining)

This repository contains the full computational workflow used for the LDA topic modeling analysis.

- **Software:** Orange Data Mining (v3.x)
- **Workflow File:** `final_workflow_k11.ows`
- **Key Parameters:**
  - **Preprocessing:** Tokenization, Lowercasing, Stopword removal (NLTK English list), and WordNet Lemmatization.
  - **Topic Modeling:** Latent Dirichlet Allocation (LDA) via Gensim.
  - **Number of Topics (K):** 11 (Selected based on coherence and perplexity scores).
  - **Passes/Iterations:** Default Orange settings.

To reproduce the results, open the `.ows` file in Orange Data Mining and link the provided dataset to the 'File' widget.
