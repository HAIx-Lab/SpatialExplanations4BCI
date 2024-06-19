# SpatialExplanations4BCI
Code for the paper "Quantifying Spatial Domain Explanations in BCI using EMD", IJCNN 2024

# Installing dependencies
Use requirements.txt with Python 3.7 or higher

# Reproducing results
Dataset: To skip the pre-processing step to generate epoch data, you may refer to this [repo](https://github.com/xiangzhang1015/Deep-Learning-for-BCI) for the dataset.

To use PyRiemmanian/Conformer/EEGNet, use the files with corresponding prefixes.
For a given architecture, there are 3 files corresponding to 3 conditions:
1. Train the model using all channel data
2. Using MI relevant data
3. Using feature relevance


extractResults.ipynb helps extract the model performance and save the results in .csv format

Notebooks with the prefix GradCAM_*.ipynb help generate spatial explanations for corresponding architecture.
These files also contain the code necessary for visualising the spatial explanations and quantifying the comparison.
