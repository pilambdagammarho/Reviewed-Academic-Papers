# Reviewed Academic Papers

This repository contains reviewed academic papers published in the field of *Machine Learning*. 
Compared to a research paper, the review paper does not report any new findings of the original research. It emphasizes an objective and neutral evaluation of the paper(s)
based on summary, classifcation, analysis and comparison.

The main characterstics of a review paper are -

1. Give an overview of the related research area.
2. Summarize the main ideas of the paper.
3. Set the paper in context with the existing work in the research area.
4. Discusses (critically) the strengths and weaknesses of the paper.
5. Evaluate way of reasoning and the employed scientifc methodology.
6. Checks the validity of the presented results and derived conclusions.
7. Comments on formal mistakes (citation, related work, figures, ...)


Following is the list of reviewed papers in the repository along with their abstract :

* **Using Artifcial Anomalies to Detect Unknown,Known Network Intrusions** - This paper reviews the work done in the direction of using artificial anomalies to detect unknown and known network intrusions using traditional inductive learning algorithms. Anomalies are events that deviate from the normal behaviour. Injecting artifcially generated anomalies
in the training data can facilitate to classify between the normal and anomalous data. Distribution-based artificial anomaly generation or DBA2 is the proposed algorithm for generating artificial anomalies. The distribution of a feature's values across the training data is used to selectively generate artificial anomalies.Sparse regions are infrequent
values of individual features in data set.Emphasis is made, to amplify the anomalies around the sparse region. This paper focuses on the arena of network based intrusions that is experimented upon pure anomaly detection models and both combined and misuse detection models.

* **Large-Scale Few-Shot Learning: Knowledge Transfer With Class Hierarchy** - This paper reviews the work done in the field of Large Scale Few-Shot Learning. The Large-Scale FSL model presented in this paper uses Knowledge Transfer with Class Hierarchy. Being a Large-Scale FSL model, it has many instances per class to train on in the source domain
but few instances per class in the target domain. The training utilizes pre-trained ResNet-50 as the feature embedding model and a hierarchical prediction net. Classification of the test classes is performed using Nearest Neighbour Search. The approach exploits the transferable visual features learned through the class hierarchy. This approach proposed by the authors significantly beats the baseline approach and other state-of-the-art methods. The feature learning model proposed by the authors can also be extended to Zero-Shot Learning problems and achieve the state of the art results.

* **Enhancing the Locality and Breaking the Memory Bottleneck of Transformer on Time Series Forecasting** - Time Series Forecasting is an approach of using historical
data to anticipate future observations. This is an imperative method utilized in various industry sectors that require assistance in forecasting the future. The authors aim to tackle Time Series Forecasting using Transformers. Transformer is stronger than its competitors like RNNs, LSTM and GRU, but it suffers from Memory Bottleneck issues when dealing with large amounts of data. The self-attention mechanism of transformer, uses point-wise linear transformation that diminishes the local context of data. This paper aims to eliminate both of these issues. The authors propose to enhance the locality of the transformers by using causal convolution in query and key transformation. They also propose a novel architecture called LogSparse Transformer which reduces memory constraint by choosing to focus on keys at certain indices and still maintaining the information flow. The proposed methods showcase better performance with less memory budget than canonical transformers as well as other baseline models.
