# Correlation Recurrent Units (CRU)
The repo is the official implementation for the paper: [Correlation Recurrent Units: A Novel Neural Architecture for Improving the Predictive Performance of Time-Series Data](https://ieeexplore.ieee.org/document/10264112)

# Usage
**Installation**

Step1: Create a conda environment and activate it
```
conda create -n CRU python==3.8 --y
conda activate CRU
```
Step2: Install related version Pytorch following [here](https://pytorch.org/get-started/previous-versions/).
```
# Suggested
conda install pytorch==2.3.1 torchvision==0.18.1 torchaudio==2.3.1 pytorch-cuda=12.1 -c pytorch -c nvidia
```
Step3: Install the required packages.
```
pip install -r requirements.txt
```

**Train & Test**
```
python Main.py
```

# Architecture
**Main concept**
**Layer structure**
**Forecasting performance**
**Ablation studies**

