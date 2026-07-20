# Graph Convolutional Network for Node Classification

A deep learning project that predicts unknown node labels from a weighted similarity graph. A custom Graph Convolutional Network propagates information between connected nodes while learning an embedding for each node, allowing the model to classify graph entities even when explicit node features are unavailable.

## Highlights

- Worked with a weighted graph containing **5,000 nodes**
- Converted the similarity matrix into a sparse message-passing representation
- Added self-loops to preserve each node's own representation
- Used learnable node embeddings as projected identity features
- Implemented a custom graph-convolution layer in TensorFlow
- Tuned the number of GCN layers, dropout, and weight decay

## Results

The best configuration used one GCN layer, 0.3 dropout, and 0.0005 weight decay.

- **Validation Macro-F1: 0.635**
- **Validation accuracy: 0.694**
- **Unknown-node Macro-F1: 0.647**
- **Unknown-node accuracy: 0.697**

## Tech Stack

`Python` · `TensorFlow` · `Keras` · `NumPy` · `scikit-learn`

## Notebook

[View the notebook](./gcn-node-classification.ipynb)

[Open in Google Colab](https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPOSITORY/blob/main/gcn-node-classification/gcn-node-classification.ipynb)
