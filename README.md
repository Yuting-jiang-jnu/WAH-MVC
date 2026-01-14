# Wasserstein-Aligned Hyperbolic Multi-View Clustering

Official PyTorch implementation for the **AAAI 2026** paper: **Wasserstein-Aligned Hyperbolic Multi-View Clustering**

This work was performed by **Rui Wang, Yuting Jiang, Xiaoqing Luo, Xiao-Jun Wu, Nicu Sebe, and Ziheng Chen**.

If you find this code or ideas useful for your research, please consider citing our paper.


## Experiments

You can reproduce the experimental results reported in the paper by enabling the pretrained model option.

### Load Pretrained Model

Set the following argument to `True` to directly evaluate the pretrained model provided by the authors:

```python
parser.add_argument(
    '--load_model',
    default=False,
    help='Testing if True or training.'
)
```

### Running the Code
```python
python main.py #Train
python main.py --load_model True #Test
```

### Requirements
```python
python>=3.9.7
pytorch>=1.7.1
numpy>=1.21.5
scikit-learn>=1.0.1
scipy>=1.7.3
geoopt>=0.5.0
```




