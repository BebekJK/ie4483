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

```
dataset/
├─ train/
│ ├─ dog/
│ └─ cat/
├─ val/
│ ├─ dog/
│ └─ cat/
└─ test/
```

3. Open and run the jupyter notebook ``main.ipynb``


## Artifacts

The folder ``artifacts`` contains important data related to the training of the model. It contains the plot of the training results as shown on ``acc.png`` and ``loss.png``, and also the weights of the trained model under ``resnet34_finetuned.pth``

## Project Team
This project is developed by: 

1. Kevin Jonathan Kusnomo (U2220214F)
2. Dave Martheen Gunawan
3. Jordan Siau