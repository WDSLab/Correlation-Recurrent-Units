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

# Layer structure

<img width="1570" height="862" alt="Image" src="https://github.com/user-attachments/assets/9319b963-4339-4b16-a1eb-70152ddb691a" />

# Forecasting performance

### Correlation-Recurrent-Units
![Image](https://github.com/user-attachments/assets/f2e2eddf-9c7b-43e0-beeb-f9f2d4b3e0e2)

### RNN
![Image](https://github.com/user-attachments/assets/9375c5d7-aefb-4024-ba36-4a221c2710d3)

### LSTM**
![Image](https://github.com/user-attachments/assets/c881b984-1e6e-4067-aee4-74ae1bbd2274)

### GRU**
![Image](https://github.com/user-attachments/assets/87ddd023-2391-4835-8ea2-0c114be980a9)
