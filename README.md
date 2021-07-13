# Bio-inspired similarity search and clustering

## Derived contributions
Example of "biological" learning for MNIST based on the paper [Unsupervised Learning by Competing Hidden Units](https://doi.org/10.1073/pnas.1820458116) by D.Krotov and J.Hopfield. If you want to learn more about this work you can also check out this [lecture](https://www.youtube.com/watch?v=4lY-oAY0aQU) from MIT's [6.S191 course](http://introtodeeplearning.com/).  

## Getting started
This contains original and modified codes for Unsupervised similarity search using Biohashing, a novel Locality Sensitive Hashing technique where the hash function is a set of synapses of dimension higher than the output with Hebbian-like weight updation rule, a development over FlyHash. We tried to recognise similar numbers from MNIST data set.\
A novel clustering algorithm has been derived from the mentioned training algorithm. We visualize the performace of this new clustering algorithm in contrast with K-means.\
We also apply this clustering algorithm in fake news detection.



## Original Author and License
(c)2018 Dmitry Krotov
-- Apache 2.0 License\
Code for Weight learning and corresponding hyperparameter tuning

## Modifications to BioHashing
2021 V S S Anirudh Sharma\
Similarity search added to use the learnt weights.

## Mean shifted Bio-clustering
Using the learning algorithm, a novel clustering algorithm has been designed. With the number of synapses now being considered as number of clusters, and the origin being shifted to the mean of the datapoints while learning, we have partitioning clustering algorithm based on angular position with respect to the mean of data points.

## Application of MSBC: FAKE NEWS DETECTION
Applying the algorithm for fake news detection, we achieve over 87% accuracy. To run the notebook:

Find the notebook directly on kaggle: https://www.kaggle.com/vanirudhsharma/unsupervised-bio-clustering-fake-news \
OR \
Training dataset: https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset \
To run the fake news classifier, download the data and extract it in ```../input``` 
