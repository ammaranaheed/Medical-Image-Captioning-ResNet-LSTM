# Caption Generation for Multi-modal Medical Images Using Deep Feature Learning

## Description

This repository contains the implementation of a deep learning-based framework for automatic caption generation from multi-modal medical images. Two image captioning models were developed by combining ResNet with Long Short-Term Memory (LSTM) networks. The repository includes the code required to preprocess the data, train the models, and evaluate their performance.

## Dataset Information

The experiments were conducted using the **ROCO (Radiology Objects in Context)** dataset.

The dataset was downloaded from Kaggle and is publicly available at:

https://www.kaggle.com/datasets

Please download the dataset from the original source before running the notebooks. The dataset is not included in this repository.

## Implemented Models

The following image captioning models are implemented:

* ResNet50 + LSTM
* ResNet101 + LSTM

## Computing Environment

* Operating System: Windows 11
* Development Platform: Kaggle Notebook
* Programming Language: Python
* Deep Learning Framework: PyTorch
* GPU: NVIDIA A100

## Requirements

The implementation requires the following Python libraries:

* torch
* torchvision
* numpy
* pandas
* nltk
* matplotlib
* Pillow
* tqdm

Install the required libraries before running the notebooks.

## Usage

1. Download the ROCO dataset from Kaggle.
2. Upload the dataset to your Kaggle workspace.
3. Open the notebook for the desired model.
4. Run all notebook cells sequentially.
5. Evaluate the generated captions using the provided evaluation metrics.

## Methodology

The proposed framework consists of the following steps:

1. Data preprocessing
2. Feature extraction using ResNet50 or ResNet101
3. Caption generation using an LSTM decoder
4. Model evaluation using standard image captioning metrics

## Evaluation Metrics

The generated captions are evaluated using the following metrics:

* BLEU-1
* BLEU-2
* BLEU-3
* BLEU-4
* METEOR
* ROUGE-L
* CIDEr
