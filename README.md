# Polynomial Factorization

# Introduction

This is an experiment where I tried to see how well could a transformer model neural network learn to decompose polynomials with integer coefficients into their irreducible factors.

# Technical
* Written for Python 3.7
* Uses keras with TensorFlow 2 and the package keras-transformer. You can install the latter via

```console
pip install keras-transformer
```

* Jupyter notebook experiment.ipynb was run on Google Colab Pro
* Dataset generated in Mathematica
* Implementation of beam search is adapted from the one found here: https://github.com/mmehdig/lm_beam_search/blob/master/beam_search.py (credit to @mmehdig)

# Other

* All datasets used in the experiment as well as the trained neural network can be downloaded from the following link: 
https://drive.google.com/drive/folders/1kG0wNXZh6q4olevjSKWV2RDJ_0720nO_?usp=sharing
* The folder ./Data generation contains the Mathematica script used to generate the dataset as well as the python script used to subsequently parse the data
