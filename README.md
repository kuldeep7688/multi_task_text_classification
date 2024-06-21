# Multi Task Text Classification 

This repo is an example of doing multi task text classification using Huggingface models. 
The highlight of this notebook is that it illustrates how there is no need to write train and evaluate functions. Instead, Trainer class from transformers library by Huggingface can be directly be customized for this use case 


## Data 
The dataset is used in this notebook is available publicly, and it is quite a huge dataset. It consists of complaints received from the consumer regarding the products and services. The dataset is available here (https://catalog.data.gov/dataset/consumer-complaint-database).

We will be using just a subset of this dataset. 