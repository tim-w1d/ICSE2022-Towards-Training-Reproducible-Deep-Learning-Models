# Replicate & run models
## ResNet
1. Create a conda environment with the libraries specified in the paper: `conda env create -f environment.yml`
2. Activate the environment: `conda activate towards-training-tf1`
3. Create a new directory, `mkdir cifar10`, `cd cifar10` and download dataset inside of it: wget https://www.cs.toronto.edu/~kriz/cifar.html 
4. Extract the dataset from the zip file: `tar -xf cifar-10-python.tar.gz`
5. Run the model tasks with `python3 ResNet.py`  

Comment: currently, this configuration does not work. I have also written a CPU environment, which can be created by using `environment-cpu.yml`.