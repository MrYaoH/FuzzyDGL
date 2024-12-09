# FuzzyDGL
The PyTorch implementation of ''[Fuzzy Representation Learning on Dynamic Graphs](https://ieeexplore.ieee.org/document/10286559)''.

## Data
The datasets are stored at . Note that, creating a new folder 'processed' for the datasets. 

## Usage
> python main.py -d CollegeMsg --pos_dim 108 --bs 32 --n_degree 64 1 --mode i --bias 1e-5 --pos_enc lp --walk_pool sum --seed 0 
