---
title: "Deep learning and multi-level featurization of graph representations of microstructural data"
date: 2023-02-19
publishDate: 2023-03-31
authors: ["R. Jones", "C. Safta", "A. Frankel"]
publication_types: ["2"]
abstract: "Many material response functions depend strongly on microstructure, such as inhomogeneities in phase or orientation. Homogenization presents the task of predicting the mean response of a sample of the microstructure to external loading for use in subgrid models and structure-property explorations. In contrast to mathematically derived homogenization techniques, data driven machine learning can provide empirical global average quantities of interest where traditional homogenization theory is lacking. Although many microstructural fields have obvious segmentations, learning directly from the graph induced by the segmentation can be difficult because this representation does not encode all the information of the full field. We develop a means of deep learning of hidden features on the reduced graph given the native discretization and a segmentation of the initial input field. The features are associated with regions represented as nodes on the reduced graph. This reduced representation is then the basis for the subsequent multi-level/scale graph convolutional network model. There are a number of advantages of reducing the graph before fully processing it with convolutional layers, such as interpretable features and efficiency on large meshes. We demonstrate the performance of the proposed network relative to convolutional neural networks operating directly on the native discretization of the data using three physical exemplars."
featured: false
publication: "*Computational Mechanics*"
doi: "10.1007/s00466-023-02300-3"
---

