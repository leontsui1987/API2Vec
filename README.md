# API2Vec

## Description
* API2Vec is a graph based API embedding method for malware detection. It first builds a graph model to represent the raw sequence. In particular, the graph model consists of i) temporal process graph (TPG) to model inter-process behavior and ii) temporal API graph (TAG) to model intra-process behavior. With such graphs, it employs a heuristic random walk algorithm to generate a number of paths that can capture the fine-grained malware behavior. By pre-training the paths using the Doc2Vec model, API2Vec is able to generate the embeddings of paths and APIs, which can further be used for malware detection.
* Please refer our "API2Vec: Learning Representations of API Sequences for Malware Detection" for more details.
* [Jiancong Cui](https://sites.google.com/view/jiancong) is the main contributor of this project.

## Key Modules
* [./API2Vec](./API2Vec): The source code and experimental data for RQ1, RQ3-5.
* [./API2Vec-TimesplitTest](./API2Vec-TimesplitTest): The source code and experimental data for RQ2.
