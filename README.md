## CDA-DGRL

Exploring Potential circRNA Biomarkers for Cancers based on Double-Line Heterogeneous Graph Representation Learning 

### Dependence

* Python 3.7.9
* PyTorch 1.10.1
* Pytorch-lightning 1.5.7
* Scikit-learn 1.0.1
* NumPy 1.17.5
* SciPy 1.7.3
* Pandas 1.3.5
* Matplotlib 3.2.2
* Tensorboard 2.7.0

**File**
- `main.py` Main program entry

### Install OpenNE
1. Refer to the [OpenNE](https://github.com/thunlp/OpenNE/tree/pytorch) configuration environment
2. To obtained drug and disease network representation by deepWalk, run
  - python -m openne --method deepWalk --input data/AllDrDiIs_train.txt --graph-format edgelist --output AllEmbedding_DeepWalk.txt --representation-size 64


### Contacts

