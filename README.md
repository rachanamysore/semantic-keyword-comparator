# Semantic Keyword Comparator

This project performs a semantic comparison between keywords extracted from a live website and a predefined list of domain-specific keywords. It uses natural language processing (NLP) techniques including KeyBERT for keyword extraction and SimCSE-BERT for semantic similarity analysis.

## Overview

The goal of this project is to help researchers, developers, and analysts evaluate how closely a website’s language aligns with domain-specific terminology. The tool can be adapted to any domain by simply changing the input keyword list and target website.

### Features

- Automated website crawling and text extraction
- Keyword extraction using KeyBERT
- Semantic similarity comparison using SimCSE embeddings
- Visual heatmap of word-to-word similarity
- Overall similarity score for both datasets

## Usage

This notebook is publicly available and intended for educational, research, and open-source use.  
You are free to use, modify, or extend this project, give proper attribution to the referenced models, libraries, and the original author.

## Folder Structure

```
semantic-keyword-comparator/
├── semantic-keyword-comparator.ipynb # Main notebook
├── README.md # Project documentation
├── requirements.txt # Python dependencies
├── .gitignore # Git ignore rules
```


## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/rachanamysore/semantic-keyword-comparator.git
   cd semantic-keyword-comparator
  
   
2. Install the required libraries:
pip install -r requirements.txt

3. Running the Notebook
Open semantic-keyword-comparator.ipynb in Google Colab or Jupyter.
Set your own website URL and domain keyword list (or use the provided defaults).
Run all cells to extract keywords, compute semantic similarity, and view results.

Technologies Used:
a. Python
b. Google Colab / Jupyter Notebook
c. KeyBERT (Keyword Extraction)
d. SimCSE (Semantic Sentence Embeddings)
e. HuggingFace Transformers
f. PyTorch
g. BeautifulSoup
h. Requests
i. Seaborn & Matplotlib (Visualization)

Example Website
This project uses Cryoshelter as an example website for keyword extraction and comparison.

Credits
1. SimCSE Model: princeton-nlp/sup-simcse-bert-base-uncased
2. Keyword extraction powered by: KeyBERT
3. Website content used for educational purposes only: Cryoshelter

License
This project is released under the MIT License.
You may reuse, modify, or distribute this project freely with appropriate attribution.