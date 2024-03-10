# Invoice data processing with Mistral LLM on local CPU


This repository focuses on invoice data processing using Mistral LLM (Local Language Model) on a local CPU. It aims to streamline the extraction, analysis, and management of invoice information, enhancing efficiency and accuracy

___

## Quickstart

1. Download the Mistral model, check models/model_download.txt for the download link.
2. Install the requirements: 

`pip install -r requirements.txt`

3. Copy text PDF files to the `data` folder.
4. Run the script, to convert text to vector embeddings and save in FAISS index: 

`python ingest.py`

5. Run the script, to process data with Mistral LLL and return the answer: 

`python main.py "retrieve invoice number value"`
