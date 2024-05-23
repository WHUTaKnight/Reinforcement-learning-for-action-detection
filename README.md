environment:
Python 3.7
PyTorch == 1.4.0 (tested)
NVIDIA GPU

data:
download activity v 1.3 dataset from http://activity-net.org/.
download thumos14 dataset from https://www.crcv.ucf.edu/THUMOS14/download.html.

codes:

data_generate.py and data_proposal.py are the codes to generate canditate action clips from the two datasets, with a transform.py to handle the data format.

use gcn_model.py and model_train.py to generate gcn features

use run to implement reinforcement learning by the help of policy.py, evaluate.py and joint_train.py
