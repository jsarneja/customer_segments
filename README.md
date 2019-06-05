# Wholesale customer segmentation
We employ several unsupervised algorithms to segment wholesale customers so as to better equip the distributor with insight into how to best structure their delivery service to meet the needs of each customer. We first conduct a `principal component analysis` (PCA) to deduce the relevant factors which drive maximum variability among variables of interest and then employ a `Gaussian Mixture model` for the segmentation

## Documentation

### Theory
---
The implementation uses the [UCI Machine Learning data](https://archive.ics.uci.edu/ml/datasets/Wholesale+customers)

### Installation
---
* Install jupyter notebook to open the main file. For new users, its recommended to install Anaconda from [here](http://docs.anaconda.com/anaconda/install/)
* Navigate to the specific folder and clone the repository using the following command:
    ```
    git clone https://github.com/jsarneja/customer_segments.git
    ```
* Open the jupyter notebook `customer_segments.ipynb`
    * Some additional datasets would be needed. Relevant links are provided in the jupyter notebook

## Contributing
---
We love pull requests from everyone. Here are some ways you can contribute:
* by reporting bugs
* by suggesting new features
* by writing or editing documentation
* by closing [issues](https://github.com/jsarneja/customer_segments/issues)