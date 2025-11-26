# README

## Introduction
This project is a simple Streamlit application that uses Transformers, PyTorch, and a fine-tuned language model to generate text. The model is loaded from the `./output/model/checkpoint-*` directory. Users can enter a prompt in the interface, and the system will generate output text in real time.
## Model Checkpoint that is needed for this project: 
https://drive.google.com/drive/u/3/folders/1QYLCb5Ur5Z5ub57i48FsAfxtDMGMKPbt
## Installation
Install all required libraries using the following command:

```
pip install transformers torch datasets pandas "transformers[torch]" streamlit
```

## Create Virtual Environment
Create and activate a Python virtual environment:

```
python -m venv .venv
```

Activate the environment (Windows PowerShell):

```
.venv\Scripts\Activate.ps1
```

## Run the Application
After activating the virtual environment, run the Streamlit app with:

```
streamlit run app.py
```
## Data from: 
https://www.kaggle.com/datasets/jrobischon/wikipedia-movie-plots?resource=download


