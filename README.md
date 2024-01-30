
**Classification of Academic Articles with Graph Neural Networks (GNN)**
*Introduction*
Datasets in the field of machine learning (ML) are diverse, ranging from traditional tabular datasets to those with complex structures like citation networks in the academic domain. This project delves into the application of Graph Neural Networks (GNN) for the classification of academic articles, with a specific emphasis on the widely-used Cora dataset.

*Objective*
The primary objective of this project is to explore and compare the performance of Graph Neural Networks with a traditional classification model. The focus is on utilizing a GNN to predict the topic of an academic article based on its textual content and citation network.

*Notebook Content*
1. Graph Neural Network Implementation
We provide a comprehensive implementation of a Graph Neural Network (GNN) from scratch. This implementation aims to enhance understanding and transparency in GNN architecture.

2. Comparison with a Traditional Model
We evaluate and compare the performance of the Graph Neural Network with a traditional classification model. This comparative analysis sheds light on the strengths and weaknesses of GNNs in the context of academic article classification.

3. Demonstration of Graph Convolutional Layer
The ultimate aim is to demonstrate the effectiveness of Graph Neural Networks in classifying academic articles. We provide an in-depth understanding of how a graph convolutional layer operates, contributing to the interpretability of the model.

Dataset Choice and Document Conversion
In this project, we opt for the Cora dataset due to its citation network structure, offering a unique challenge for academic article classification. The choice is motivated by the availability of structured data on articles, providing a practical alternative to PDF documents that may not always be easily accessible online.

Document Conversion for General Applicability
To extend the applicability of the techniques presented, we include code within this notebook for converting any document into a binary vector representation. This functionality enables the application of the classification methods discussed here to domains where structured data is not readily available. The relevant code, located at the end of the notebook, facilitates the conversion and classification of documents in various contexts.

*Dependencies*
Libraries: PyTorch, NetworkX, Scikit-learn, NumPy
Usage
Install the required dependencies.
Run the notebook cells in sequence.
Acknowledgments
The Cora dataset is used in this project. Acknowledgments to the original authors and contributors.
