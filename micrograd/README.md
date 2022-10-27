# Code-along tutorial on backpropagation and automatic differentiation

This is the page for the code-along sessions of the ML and analytics SIGs, based on [this video by Andrej Karpathy](https://www.youtube.com/watch?v=VMj-3S1tku0) and his corresponding repository [micrograd](https://github.com/karpathy/micrograd).

## Setup

The tutorial has some prerequisites, so we go over them step by step. Additionally, the video has some copy-pasted code in a handful of places that might be too fast to type along, we have collected these in a notebook.

### Run on Google Colab
The easiest is to open this notebook in Google Colab by clicking this button: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NLeSC/Machine_Learning_SIG/blob/master/micrograd/copy_pasta.ipynb)

### Run locally
If you prefer to run it locally, we suggest creating a conda environment and setting up jupyter with the following steps:
```
conda create --name=micrograd python=3.9
conda install jupyter
conda install numpy
conda install matplotlib
pip install graphviz
```
if you wish to compare your results to pytorch also install pytorch
```
conda install pytorch
```

Once everything is installed you can then download the notebook `copy_pasta.ipynb` and open jupyter with
```
jupyter notebook
```
