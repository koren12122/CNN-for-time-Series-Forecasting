# CNN-for-time-Series-Forecasting

The aim of this project is to construct a precise prediction model that can effectively forecast resource consumption in K8. This will be accomplished by utilizing time-series data on CPU/Memory usage gathered from Prometheus. The model will learn from this data and accurately predict future resource usage.
The model that we choose is a CNN based on the paper  [An Experimental Review on Deep Learning Architectures
for Time Series Forecasting](https://doi.org/10.1142/S0129065721300011)



## Background:
K8 is an open source software that manages, automates, deploys and hosts containerized applications.

#### What is a K8 Cluster
A Kubernetes cluster is a set of node machines for running containerized applications. If you’re running Kubernetes, you’re running a cluster.

#### What is a K8 Node
Nodes are comprised of physical or virtual machines on the cluster that run the pods; these “worker” machines have everything necessary to run your application containers, including the container runtime and other critical services.

#### What is a K8 Pod
This is essentially the smallest deployable unit of the Kubernetes ecosystem. A pod specifically represents a group of one or more containers running together on your cluster.

#### What is a K8 Container
Each container that you run is repeatable; the standardization from having dependencies included means that you get the same behavior wherever and wherever you run it.
consists of an entire runtime environment of a task. Such as the application code, needed libraries and more.

#### What is a K8 Namespace
A virtual cluster. Namespaces allow Kubernetes to manage multiple clusters (for multiple teams or projects) within the same physical cluster.


### Prometheus:
Prometheus is an open-source monitoring system. Prometheus uses Kubernetes and collects time-series data on running pods, nodes and more. The collected metrics are CPU usage, Memory usage. The data collected gives the users an apprehensive insight into their applications whilst providing real-time metrics that would help them problem-solve.
### Installation
```
$ python3 install matplotlib
$ python3 install pandas
$ python3 install sktime
$ python3 install numpy
$ python3 install torch
```

### Results
![Example 1]([image_url](https://github.com/koren12122/CNN-for-time-Series-Forecasting/blob/master/graph1.png))
![Example 2]([image_url](https://github.com/koren12122/CNN-for-time-Series-Forecasting/blob/master/graph2.png))

