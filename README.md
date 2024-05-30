# WITBIT
An Improv Scene Partner LLM

Repository Structure
```plaintext
improv-rag/
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
