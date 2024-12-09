# FuzzyDGL
The PyTorch implementation of ''[Fuzzy Representation Learning on Dynamic Graphs](https://ieeexplore.ieee.org/document/10286559)''.

## Requirements
- numpy         1.19.2
- python        3.6.13
- pytorch       1.7.1
- scikit-learn  0.24.2
- scipy         1.5.4
- numpy         1.19.2

## Data
The datasets are stored at [Download](https://drive.google.com/drive/folders/1FwiDUCK4KSL0E3w3IdR9Iek87dho-hu3). 

Note that, one should create a new folder 'processed' for the datasets. 

## Usage
Train and evaluate the model by executing
> python main.py -d CollegeMsg --pos_dim 108 --bs 32 --n_degree 64 1 --mode i --bias 1e-5 --pos_enc lp --seed 0 
