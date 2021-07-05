# GCN_complex_detection

These are two folders in this repository. 

## Datasets:
Four datasets are being used throughout this work. Folders in the Datasets folder are corresponding to each of the datasets. Human, Mouse, and Collins datasets have PPI network and reference complexes. Gavin folder contains complexes obtained from four different methods along with PPI network and reference complexes. 

**Human_and_mouse_datapreprocessing.ipynb** is used to preprocess Human and Mouse datasets. Collins and Gavin datasets are directly used in the provided implementations.

## Implementations:

This folder contains the implementation of all the methods. Python notebooks in this folder use the datasets mentioned. 

There are seven notebooks in this folder. The descriptions of these notebooks are as follows.

1. **multi_class_GCN_on_collins_with_2^N_labels.ipynb:** This notebook uses the multi-class GCN method for complex detection. The length of any label in this implementation is 2^N, where N is the total number of complexes. 

2. **GCN_toy_example.ipynb:** It illustrates the working of multi-class GCN on a dummy example. 

3. **Multi_label_GCN_on_collins.ipynb:** This notebook provides the implementation of multi-label GCN classification on the Collins dataset.

4. **NOCD_approach_&_evaluation.ipynb:** This notebook provides the implementation of NOCD approach for complex detection.

5. **Human_Feature_Generation_and_results.ipynb and Mouse_Feature_Generation_and_results.ipynb:** These notebooks implement multi-class GCN feature extractor and clustering on Human and Mouse datasets. The length of any label in these implementations is the total number of possible combinations of labels. 

6. **Cluster_Aggregation.ipynb:** This notebook provides the aggregation method of clusterings obtained from different methods. 

**Note:** File paths of datasets should be at appropriate place in these notebooks. 









