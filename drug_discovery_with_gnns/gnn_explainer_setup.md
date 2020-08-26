# Installation Tips for GNNExplainer (Windows 10 + CUDA Enabled GPU)
```
# Setting up a repo
git clone https://github.com/RexYing/gnn-model-explainer.git
# Creating conda environment
conda create -n "gnn_env" python=3.7
conda activate gnn_env

# Installation
conda install pytorch torchvision cudatoolkit=10.1 -c pytorch
conda install -c conda-forge opencv
conda install matplotlib networkx pandas scikit-learn seaborn
conda install -c conda-forge tensorboardx
conda install tensorboard
conda install -c anaconda jupyter
```

# Running a Demo (syn1 dataset)
To train the model on syn1 graph dataset, run the following command in the project repository:
`python train.py --dataset=syn1`