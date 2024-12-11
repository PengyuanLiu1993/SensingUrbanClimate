# SensingUrbanClimate

This repo is a host of codes for the paper *Sensing Climate Justice: A Multi-Hyper Graph Approach for Classifying Urban Heat and Flood Vulnerability through Street View Imagery* published in Sustainable Cities and Society (doi: https://doi.org/10.1016/j.scs.2024.106016)

<img src="https://github.com/PengyuanLiu1993/SensingUrbanClimate/blob/main/ucj_github.png/">

This repo contains two jupyternote book files: London_dataProcess.ipynb and multi_hyper.ipynb. London_dataProcess.ipynb is a demonstration of how to prepare the graph data for street view images in London, and multi_hyper.ipynb conatins our proposed Multi-Hyper Graph Neural Network and training demonstration. Note that we do not explicitly demonstrate how the connections of the graphs from polygon data were extracted in this repo because, first, many of the data were extracted by QGIS (hence, non-code related), and second, how people want to construct the graphs for their spatial analytics are task- and also geography-dependent. If you are interested in how the graphs were constructed in detail, please refer to our paper for detailed discussions. 

The following Package for the execution of the codes will be required:

1. PyG (PyTorch Geometric)
2. Networkx
3. Pandas
4. geopandas
5. libpysal
6. shapely
7. jenkspy
