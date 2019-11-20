# MLADs2019Fall-Interpretability
This is a repo for use in our MLADs Lab in Fall 2019.

## Get access to the notebook VM
Registration URL : http://bit.ly/32yBHhI

Fill out name, email, etc.

An email with access link and password should follow in 10 – 15 minutes.​

Please use Chrome to open! Incognito helps.

## Setup the kernel
In the New menu, create a Python 3.5 notebook

In the first cell put:

!git clone https://github.com/bethz/MLADs2019Fall-Interpretability.git​

!python -m pip install azureml-contrib-interpret --upgrade​


## Start the first notebook

From the root directory, go to:​

/MLADs2019Fall-Interpretability/MLADS-Local/​

blackbox-simple-feature-transformations-explain-local.ipynb

## Setup the second notebook
Go back to the email you received and get the Azure Machine Learning ODSC username and password​

Use them to access portal.azure.com​

Go to the created Azure ML resource (quick-starts-ws-*)​

Download config.json and upload it to root

## Start the second notebook
Launch blackbox-train-explain-model-on-amlcompute-and-deploy.ipynb

