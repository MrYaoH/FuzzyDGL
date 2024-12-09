# FuzzyDGL
The PyTorch implementation of ''[Fuzzy Representation Learning on Dynamic Graphs](https://ieeexplore.ieee.org/document/10286559)''.

## Data
The datasets are stored at [Download](https://drive.google.com/drive/folders/1FwiDUCK4KSL0E3w3IdR9Iek87dho-hu3). 

Note that, one should create a new folder 'processed' for the datasets. 

## Usage
Train and evaluate the model by executing
> python main.py -d CollegeMsg --pos_dim 108 --bs 32 --n_degree 64 1 --mode i --bias 1e-5 --pos_enc lp --seed 0 
