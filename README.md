## Neuro_Segmentation
Neuro_Seg: Matlab tool for segmentation of mice neurons. 
G.Zhu
5-11-2020

Segmentation tool that help with identification of brain cells for morphological studies of WT mice neuron. Primary objective of the tool is to assist in identification of neuron size in health and cognitive impairment WT mice.

## The primary steps of Neuro_Seg includes: 
1) Enhancement*
2) Segmentation
3) Thresholding with histogram
4) Construct binary threshold map based on image histogram
5) Clustering of neuron
6) Filtering small neurons
7) Segmentation with color based on neuron size (displayed with alpha map)

The segmented neurons will be assigned into different color based on the neuron size. Thresholding was selected based on histogram of the raw input image. Smaller neurons were ignored to better study mature neuron morphology from the cluster. 

## Source: 
http://atlas.brain-map.org/atlas?atlas=1&plate=100960324#atlas=1&plate=100960324

