# Caption Generation for Multi-modal Medical Images Using Deep Feature Learning

## Description

In this repository, we have provided an implementation of an auto-captioning system based on a deep learning approach for generating captions from multi-modal medical images. We have developed two different systems of image captioning that were made using the combination of ResNet architecture with LSTM networks.

## Dataset Information

The experiments were conducted using the **ROCO (Radiology Objects in Context)** dataset.

The dataset was added from Kaggle and is publicly available at:

(https://www.kaggle.com/datasets/virajbagal/roco-dataset/data)


## Implemented Models

The following image captioning models are implemented:

* ResNet50 + LSTM
* ResNet101 + LSTM

## Computing Environment

* Operating System: Windows 11
* Development Platform: Kaggle Notebook
* Programming Language: Python
* Deep Learning Framework: PyTorch
* CPU

## Requirements

The implementation requires the following Python libraries:

* torch
* torchvision
* numpy
* pandas
* nltk
* matplotlib
* tqdm
* PIL

Install the required libraries before running the notebooks.

## Usage

1. Download the ROCO dataset from Kaggle.
2. Load the ROCO dataset into your Kaggle environment.
3. Load the notebook for the required model.
4. Execute all the cells in the notebook in order.
5. Assess the captions created through the evaluation metrics.

## Methodology

The following steps comprise the suggested framework:

1. Preprocessing of data
2. Feature extraction through ResNet50 or ResNet101
3. Caption creation with an LSTM decoder
4. Evaluation of the model through common image captioning metrics

## Evaluation Metrics

The generated captions are evaluated using the following metrics:

* BLEU-1
* BLEU-2
* BLEU-3
* BLEU-4
* METEOR
* ROUGE-L
