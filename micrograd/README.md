# Code-along tutorial on backpropagation and automatic differentiation

This is the page for the code-along sessions of the ML and analytics SIGs, based on [this video by Andrej Karpathy](https://www.youtube.com/watch?v=VMj-3S1tku0) and his corresponding repository [micrograd](https://github.com/karpathy/micrograd).

## Setup

The tutorial has some copy-pasted code in a handful of places that might be too fast to type along, we have collected these in a notebook. 

The easiest is to open this notebook in Google Colab by clicking this button: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NLeSC/Machine_Learning_SIG/blob/micrograd/copy_pasta.ipynb)

If you prefer to run it locally, we suggest creating a conda environment and setting up jupyter lab with the following steps:
```
conda create --name=micrograd
conda activate
conda install ipykernel
ipython kernel install --user --name=micrograd
conda install -c conda-forge jupyterlab
```

and then downloading the notebook `copy_pasta.ipynb` and opening jupyter with 
```
jupyter lab
```
The dependencies `graphviz` for visualization and `numpy` and `pytorch` just for comparison are installed in the notebook itself.
