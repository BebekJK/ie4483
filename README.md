# Dogs vs Cats Image Classification 🐶🐱

A deep learning project for IE4483: Artificial Intelligence and Data Mining at Nanyang Technological University, focused on building and evaluating an algorithm that distinguishes between images of dogs and cats.

## Setup

1. Create a python virtual environment. Use any python version >= 3.9.

``` bash
python3 -m venv .venv # create a viritual environment named .venv
source .venv/bin/activate # activate venv
pip install -r requirements.txt # install required library
```

2. Make sure the dataset is already in your directory with this structure

```txt
# Cat and Dog Dataset
dataset/
├─ train/
│ ├─ dog/
│ └─ cat/
├─ val/
│ ├─ dog/
│ └─ cat/
└─ test/

# CIFAR-10 Dataset
cifar-10-batches-py/
├─ batches.meta
├─ data_batch_1
├─ data_batch_2
├─ data_batch_3
├─ data_batch_4
├─ data_batch_5
├─ readme.html
└─ test_batch
```
If you haven't had the dataset, you can download it [here](https://www.cs.toronto.edu/~kriz/cifar.html) for the Cat & Dog dataset, and [here](https://drive.google.com/file/d/1q0r6yeHQMS17R3wz-s2FIbMR5DAGZK5v/view?usp=sharing) for the CIFAR-10 dataset.

3. There are 3 different notebooks used for developing the model, ``cat_dog_finetune.ipynb``, ``cat_dog_tinyvgg.ipynb`` and ``cifar_10.ipynb``, and 1 notebook used for the evaluation, ``evaluation.ipynb``. Once all the requirements are completed, open one of the notebook and run the cells.


## Artifacts

The folder ``artifacts`` contains important data related to the training of the model. It contains the plot of the training results as shown on ``acc.png`` and ``loss.png``

## Project Team
This project is developed by: 

1. Dave Martheen Gunawan (U2220581K)
2. Jordan Siau (U2221866G)
3. Kevin Jonathan Kusnomo (U2220214F)