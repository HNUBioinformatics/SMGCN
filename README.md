# SMGCN：:A Similarity Fusion and Multi-kernel Fusion-Based Graph Convolutional Neural Network for Drug-Target Interaction Prediction

# Dataset
The number of known drugs targeting enzymes, ion channels, GPCRs, and nuclear receptors is 445, 210, 223, and 54, respectively, and the number of target proteins in these classes is 664, 204, 95, and 26, respectively. After careful examination of these drug-target pairs, the number of known interactions involving enzymes, ion channels, GPCRs and nuclear receptors is 2926, 1476, 635 and 90, respectively.

# Requirements
* Python 3.7
* Pytorch
* PyTorch Geometric
* numpy
* scipy

# code
* clac_metric.py:  evaluating indicator
* loss.py:  loss function
* processing.data.py:  processing data
* utils.py:   Initial function
* SMGCN.py:  Model
* Main:   Main function
