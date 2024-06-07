# AthenaRec (Open Source Software Recommendation)

## 📝 Introduction
AthenaRec is a multilingual large-scale open source software recommendation system based on AI technology, designed to recommend the most suitable software for developers from a vast array of OSS options based on their specific requirements.

## 🛠️ Installation

AthenaRec runs in the Python environment. Please ensure your Python version is higher than 3.9.

Installation dependency using pip command:
```shell
pip install -r requirements.txt
```
treet
## 🔥 Code Structure 
```markdown
├── conf                         # config file
│   ├── cn_key_words.json
│   ├── cn_trans_en.json
│   ├── depend_softwares.json
│   ├── dirty_words.txt
│   ├── key_name_words_2.json
│   └── tmp_key_words.txt
├── config.py                    # Software industry scenario labels
├── data                         # data file
│   ├── emb_keywords.json
│   ├── software_data.csv
│   └── tag_embs.npz
├── deploy.sh                    # Deployment script
├── intent_recognition_model     # Intention Recognition Model
│   └── saved_models
├── text_similarity_models       # Text similarity model
│   └── SimCSE-2023-03-09_11-22-22
├── intent_recognition.py        # Intention Recognition script
├── load_data.py                 # Data loading script
├── main.ipynb                   # Presentation of recommended results
├── model.py                     # Model Definition Script
├── README.md
├── requirements.txt             # Develop environment dependeny
├── server.py                    # Service startup script
├── software_recommend.py        # Software recommendation(Delphi+Argus+Hestia)
└── utils.py                     # Tool Script
```

## 🚀 Getting Started

For specific usage, please refer to the **[main.ipynb](./main.ipynb)** file.
