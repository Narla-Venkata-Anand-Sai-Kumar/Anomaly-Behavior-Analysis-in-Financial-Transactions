---

# Anomaly Behavior Analysis in Financial Transactions

This repository contains code and resources for analyzing anomalous behavior in financial transactions using graph neural networks (GNNs). The goal is to identify patterns and detect fraudulent activities within credit card transactions.

## Dataset

The dataset used for this analysis can be downloaded from [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud). It consists of labeled credit card transactions, with features anonymized due to privacy concerns. Please ensure you have downloaded and prepared the dataset before running the code.

## GNN Build

The `GNN_BUILD` directory contains the code for building and training the graph neural network model.

To run the GNN model, navigate to the `GNN_BUILD` directory in your terminal and execute the following command:

```bash
cd GNN_BUILD/
python gnn.py --model gcn --dataset YelpChi --epochs 10 --runs 5 --device 0
```

Make sure to adjust the parameters according to your preferences. Here's a breakdown of the parameters used:
- `--model`: Specify the GNN model architecture (e.g., GCN).
- `--dataset`: Input dataset name or path.
- `--epochs`: Number of training epochs.
- `--runs`: Number of runs for training.
- `--device`: Specify the device to run the training on (e.g., GPU index).

## Jupyter Notebook

The Jupyter Notebook included in this repository (`Anomaly_Patterns.ipynb`) provides visualizations and analyses of detected anomalies and their patterns within the financial transaction data. Open the notebook in a Jupyter environment to explore and visualize the detected patterns.

---