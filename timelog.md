# Timelog

* Identifying Motifs of Tumour Tissue Architecture with Deep Representation Learning
* Shorya Singh
* 2224727
* Dr Ke Yuan

## Week 1
### 28 Sept 2021
* *2 hours* Attended the level 4 project launch meeting

### 29 Sept 2021
* *3 hours* Studied the research papers on which the project is based
* *1 hour* Researched general terminoly related to pathology required for the project

### 30 Sept 2021
* *2 hours* Researched unsupervised learning

### 1 Oct 2021
* *2 hours* Researched representation learning techniques
* *2 hours* Researched how GANs work


## Week 2
### 4 Oct 2021
* *2 hours* Reaserched Pathology GAN and related models for representation learning

### 5 Oct 2021
* *2 hours* Researched clustering techniques for high dimensional data
* *1 hour* Came up with an appropriate scope for the project based on the feasibility of completing the project within the timeframe of the academic year 

### 6 Oct 2021
* *1 hour* Came up with a high level pipeline which could be used to structure/cluster unsupervised data
* *1 hour* Researched potential evaluation metrics to evaluate image clusters 

### 8 Oct 2021
* *0.5 hour* Set up version control with appropriate project template
* *0.5 hour* Attended the **first** meeting with the supervisor 
* *1 hour* Reflected on and redefined the scope of the project based on the idea the supervisor has for the project

### 10 Oct 2021
* *0.5 hour* Set up Zotero and transfered all the references so far to Zotero


## Week 3
### 11 Oct 2021
* *1 hour* Go over the paper N2D: (Not Too) Deep Clustering via Clustering the Local Manifold of an Autoencoded Embedding

### 12 Oct 2021
* *2 hours* Researched about prinipal component analysis along with potential pipelines to use it for clustering

### 13 Oct 2021
* *1 hour* Researched about H5py file format and read the documentation
* *0.5 hour* Set up a jupyter notebook for experimentation on the data

### 14 Oct 2021
* *1 hour* Explorde the dataset
* *1 hours* Wrote a script to match the image representation data to the patient mutation data based on barcode

### 15 Oct 2021
* *2 hours* Explored the principal components of the data and visualized the trends about the variance of different number of principal components
* *2 hours* Plotted kmeans inertia scores with different k numbers to figure out best number of centroids for 2 principal components which show most variance
* *1 hour* Ran kmeans with the 2 principal components

### 16 Oct 2021
* *2 hours* Visualized the clusters and centroids and tried to come up with theories based on what I saw

### 17 Oct 2021
* *3 hours* Ran kmeans on all the features and visualized the clusters on the 3 principal components. Plotted different views of the clusters to theorize why the clusters are so close to each other

## Week 4

### 18 Oct 2021
* *1 hour* researched on how to plot interactive plots to easily see differnt angles of the plot. Plotted interactive plots

### 19 Oct 2021
* *2 hours* Analysed clusters using Silhouette Coefficient
* *1 hour* Met with the advisor and other people involved in research

### 20 Oct 2021
* *3 hours* Read papers on dimentionality reduction - umap, t-sne

### 21 Oct 2021
* *1 hour* Organized jupyter notebook to make it suitable/presentable for sharing
* *1 hour* Prepared summary powerpoint presentation of work done so far

### 23 Oct 2021
* *2 hours* A first look at the 100k dataset, set up a framework to match the 100k dataset to the gene mutation dataset
* *2 hours* Researched deep clustering options

### 24 Oct 2021
* *2 hours* Looked for suitable implementations of DEC and decide on the most straightforward implementation
* *2 hours* Familiriarized with deep embedded clustering along with sample cluster analysis

## Week 5

### 26 Oct 2021
*1 hour* Weekly AI pathology meating

### 29 Oct 2021
* *4 hours* Tried out the implementation of DEC, and initialized it with toy dataset
* *2 hours* Made changes to an existing implementation of DEC to make it compatible with latest packages 
* *1 hour* Made changes to the DEC code to get rid of an attribute error  

### 30 Oct 2021
* *2 hours* Sampled from the dataset to reduce data points, made the notebook compatible for work in colab
* *2 hours* Initialized DEC setup
* *1 hour* Saved autoencoder weights after the clutering failed due to a namespace error
* *1 hour* Reinitialized the DEC setup with weights from previous pretraining 

### 31 Oct 2021
* *1 hour* Troubleshoot the clustering in which I used PathologyGAN representations as input 


## Week 6
### 1 Nov 2021
* *4 hours* Configured DEC implementation to be compatible with GPU

### 2 Nov 2021
* *4 hours* Changed the DEC implementation to make it use GPU and reconfigured tensorflow -GPU

### 5 Nov 2021
* *2 hours* Configured keras backend to make it use tensorflow

### 7 Nov 2021
* *5 hours* Configured keras backend settings to make training possible in the cloud environment using GPU 

