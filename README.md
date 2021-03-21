# Polynomial Factorization

# Introduction

This is an experiment where I tried to see how well could a transformer model learn to decompose polynomials with integer coefficients into their irreducible factors.

# Technical
* Written for Python 3
* Uses keras with TensorFlow 2 and the package keras-transformer. You can install the latter via

```console
pip install keras-transformer
```

* Jupyter notebook experiment.ipynb was run on Google Colab Pro
* Dataset generated in Mathematica

# Other

* All datasets used in the experiment as well as the trained neural netowrk can download from the following link: 
https://drive.google.com/drive/folders/1kG0wNXZh6q4olevjSKWV2RDJ_0720nO_?usp=sharing
* The folder ./Data generation contains the Mathematica script used to generate the dataset as well as the python script subsequently used to parse the data generated by Mathematica.