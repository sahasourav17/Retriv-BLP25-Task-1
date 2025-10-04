# Retriv at BLP25 Task 1: Hate Speech Detection

This repository contains the notebooks, code and necessary files for our submissions to **Task 1: Hate Speech Detection** organized by the BLP Workshop at IJCNLP-AACL 2025. It includes scripts for data preprocessing, model training and evaluation, as well as configuration files required to reproduce our results.  

For more details on the shared task, visit the [Task 1 webpage](https://multihate.github.io/), [Leaderboard](https://github.com/AridHasan/blp25_task1?tab=readme-ov-file#leaderboard) and the [BLP Workshop homepage](https://blp-workshop.github.io/).


# Notebooks Overview

This directory contains notebooks for all three subtasks of **Task 1: Hate Speech Detection**.

## Folder Structure:
```
notebooks/
├── Subtask-1A
│   ├── BanglaBERT.ipynb
│   ├── bi-gru
│   │   ├── bi-gru-fasttext.ipynb
│   │   └── bi-gru-glove.ipynb
│   ├── bi-lstm
│   │   ├── bi-lstm-fasttext.ipynb
│   │   └── bi-lstm-glove.ipynb
│   ├── ensemble.ipynb
│   ├── IndicBERT.ipynb
│   └── MuRIL.ipynb
├── Subtask-1B
│   ├── BanglaBERT.ipynb
│   ├── bi-gru
│   │   ├── bi-gru-fasttext.ipynb
│   │   └── bi-gru-glove.ipynb
│   ├── bi-lstm
│   │   ├── bi-lstm-fasttext.ipynb
│   │   └── bi-lstm-glove.ipynb
│   ├── ensemble.ipynb
│   ├── IndicBERT.ipynb
│   └── MuRIL.ipynb
└── Subtask-1C
    ├── BanglaBERT.ipynb
    ├── ensemble-muril-bert-indic.ipynb
    ├── IndicBERT.ipynb
    └── MuRIL.ipynb
```

## Subtask-1A
- **BanglaBERT.ipynb** – Fine-tuning BanglaBERT for hate type classification.  
- **bi-gru/** – Bi-GRU based models with:
  - `bi-gru-fasttext.ipynb`  
  - `bi-gru-glove.ipynb`  
- **bi-lstm/** – Bi-LSTM based models with:
  - `bi-lstm-fasttext.ipynb`  
  - `bi-lstm-glove.ipynb`  
- **IndicBERT.ipynb** – Fine-tuning IndicBERT.  
- **MuRIL.ipynb** – Fine-tuning MuRIL.  
- **ensemble.ipynb** – Ensemble of MuRIL, IndicBERTv2, and BanglaBERT (soft, hard, weighted).

## Subtask-1B
- Same structure as Subtask-1A but focused on target group identification.

## Subtask-1C
- **BanglaBERT.ipynb** – Multitask learning approach.  
- **IndicBERT.ipynb** – Multitask learning approach.  
- **MuRIL.ipynb** – Multitask learning approach.  
- **ensemble-muril-bert-indic.ipynb** – Ensemble of MuRIL, IndicBERTv2, and BanglaBERT using soft, hard, and weighted strategies for multitask learning.



## Citation
```bibtex
@InProceedings{BLP2025:task1:Retriv,
    author = {Saha, Sourav and Asib, K M Nafi and Hoque, Mohammed Moshiul},
    title = "Retriv at BLP-2025 Task 1:A Transformer Ensemble and Multi-Task Learning Approach for Bangla Hate Speech Identification",
    booktitle = "Proceedings of the 2nd Workshop on Bangla Language Processing (BLP 2025)",
    month = dec,
    year = "2025",
    address = "Mumbai, India",
    publisher = "Association for Computational Linguistics",
}

```