# MaNGA-reconstruction

## shell environment setup, e.g. replace with your path as appropriate
```
export RECONSTRUCTION_DIR=/mnt/c/Users/dacb/Desktop/MaNGA-reconstruction
```

## python environment setup
* setup empty conda environment using intended version of python, e.g. 3.5
```
conda create -n manga python=3.5
conda activate manga
```
* use pip to install dependencies (because marvin is only pip installable)
```
pip install sdss-marvin
```
#### Note: on dacb's machine this brought along all other necessary dependencies

## run the code with:
```
cd python
python reconstruction/reconstruct.py
```
