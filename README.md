# EDABE_LSTM_1DCNN

This repository shows how to use EDABE LSTM-1D CNN Model to correct artifacts automatically in Electrodermal Activity (EDA) signal. To learn how to use the model, EDABE_LSTM_1DCNN_ModelExample.ipynb shows how to charge the model and the needed functions to pre-process and post-process the output of the signal. A random signal is choosen from the test set of [EDABE](https://data.mendeley.com/datasets/w8fxrg4pv5) dataset to show the performance of the model. The model itself can be found in the folder Model. 

This algorithm is part of a research work which is under a submission.


# Getting Started

This repo is tested with Python 3.10. To install the required packages, run the following command:

```bash
pip install -r requirements.txt
```

# Usage

* EDABE_LSTM_1DCNN_ModelExample.ipynb: this notebook is from the original repository and is using an old version of tensorflow. You should instead use EDABE_LSTM_1DCNN.py.
* EDABE_LSTM_1DCNN.py: this script is the same as the notebook but with the updated version of tensorflow.
* EDABE_LSTM_1DCNN_PTSD: this script is the same as EDABE_LSTM_1DCNN.py but with the PTSD dataset. To run this script, you will need to change the path to the dataset in the script. For more information, please refer to dosctring at the top of the script.