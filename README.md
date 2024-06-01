# WITBIT

## :ledger: Index

- [About](#beginner-about)
- [Development](#wrench-development)
  - [File Structure](#file_folder-file-structure)

##  :beginner: About
Purpose: Improv Scene Partner LLM

Implementation: (Retrieval-Augmented Generation) system employing a fine-tuned OpenAI model designed to enhance improvisational dialogue response quality for virtual scene partners.

Data Curation Methodology: 


##  :wrench: Development
###  :file_folder: File Structure
## Envisioned Finished Repo Structure:
> *Note: This repo structure represents the goal of the final project and the first milestone is to have an MVP that will not include improv coaching (notes & feedback) feature*
```plaintext
WITBIT/
├── data/
│   ├── scenes/
│   │   ├── scene1.json
│   │   ├── scene2.json
│   │   └── ...
│   ├── feedback/
│   │   ├── feedback1.json
│   │   ├── feedback2.json
│   │   └── ...
├── models/
│   ├── finetuned_gpt/
│   │   ├── config.json
│   │   ├── pytorch_model.bin
│   │   └── ...
│   ├── retriever/
│   │   ├── retriever_model/
│   │   └── ...
├── scripts/
│   ├── train_retriever.py
│   ├── preprocess_data.py
│   └── ...
├── src/
│   ├── __init__.py
│   ├── app.py
│   ├── config.py
│   ├── retrieval.py
│   ├── generation.py
│   ├── feedback.py
│   └── utils.py
├── tests/
│   ├── test_app.py
│   ├── test_retrieval.py
│   ├── test_generation.py
│   ├── test_feedback.py
│   └── ...
├── Dockerfile
├── requirements.txt
└── README.md
```
