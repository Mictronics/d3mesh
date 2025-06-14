# Interactive force-directed network creator (d3graph)

``d3graph`` is a python package that simplifies the task of creating **interactive** and **stand-alone** networks in **d3 javascript** using **python**.
For this package I was inspired by d3 javascript examples but there was no python package that could create such interactive networks. Here it is; a library that automatically creates D3 javascript and HTML code based on an input adjacency matrix in python! This library does not require you any additional installation, downloads or setting paths to your systems environments. You just need python and this library. All other is taken care off. Huray!

This library will create an interactive and stand-alone network that is build on d3 javascript. ``d3graph`` only requirs an adjacency matrix in the form of an pandas dataframe. Each column and index name represents a node whereas values >0 in the matrix represents an edge. Node links are build from rows to columns. Building the edges from row to columns only matters in directed cases. The network nodes and edges can be adjusted in weight, color etc, based on user defined paramters. 

## [Documentation pages](https://erdogant.github.io/d3graph/)

On the [documentation pages](https://erdogant.github.io/d3graph/) you can find detailed information about the working of the ``d3graph`` with many examples. 

### Installation

##### Install from PyPI

```bash
pip install d3graph
```

##### Import package

```python
from d3graph import d3graph
```
