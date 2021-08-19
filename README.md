# GCN: SEMI-SUPERVISED CLASSIFICATION WITH GRAPH CONVOLUTIONAL NETWORKS 

Paper Reference: https://arxiv.org/abs/1609.02907

### Install the requirement libraries

```git
!pip install -q torch-scatter -f https://pytorch-geometric.com/whl/torch-1.9.0+cu102.html
!pip install -q torch-sparse -f https://pytorch-geometric.com/whl/torch-1.9.0+cu102.html
!pip install -q torch-geometric
```

### Clone the repository

```git
!git clone https://github.com/Ahmed-A-A-Elhag/GCN
```

### Train the model of Cora dataset

```git
!python GCN/src/main.py  --num-epochs 200 --data 'Cora' --num-hid  16 --num-class 7 
```
