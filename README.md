This repository contains the code for all experiments in the paper "Interpretability in the Wild: a Circuit for Indirect Object Identification in GPT-2 Small" (Wang et al, 2022).

For now, it may be easier to view an earlier version of the experiments at https://drive.google.com/file/d/1kFpJdqIEgjFVJRb5FpdPyuluXq6fUPb_/view . The code in this repository is a work in progress. 

Contact arthur@rdwrs.com for help running code, etc.

# Setup

## Install dependencies

```bash
pip install -r requirements.txt
```

# In this repo

In this repo, you can find

* `experiments.py`: a notebook of several of the most interesting experiments of the IOI project.
* `ioi_completeness.py`: a notebook that generate the completeness plots in the paper, and implements the completeness functions.
* `ioi_minimality.py`: as above for minimality.
* `ioi_advex.py`: a notebook that generates adversarial examples as in the paper.
* `ioi_utils.py`: a collection of utility functions for the above notebooks.

# Easy Transformer

## An implementation of transformers tailored for mechanistic interpretability.

It supports the importation of open sources models, a convenient handling of hooks 
to get access to intermediate activations and features to perform simple emperiments such as ablations and patching.

A demo notebook can be found [here](https://colab.research.google.com/github/neelnanda-io/Easy-Transformer/blob/main/EasyTransformer_Demo.ipynb) and a more comprehensive description of the library can be found [here](https://colab.research.google.com/drive/1_tH4PfRSPYuKGnJbhC1NqFesOYuXrir_#scrollTo=zs8juArnyuyB)


## Installation

`pip install git+https://github.com/neelnanda-io/Easy-Transformer`
