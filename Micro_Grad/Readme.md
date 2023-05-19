## Artificial Neural Network (ANN)
&rarr; An Artificial Neural Network (ANN) is an information processing paradigm that is inspired by the brain. ANNs, like people, learn by examples. An ANN is configured for a specific application, such as pattern recognition or data classification, through a learning process.

![ANN Image](https://s3.amazonaws.com/stackabuse/media/intro-to-neural-networks-scikit-learn-3.png)

## Backpropagation
&rarr; Backpropagation is a standard method of training artificial neural networks. It is a process involved in training a neural network. It involves taking the error rate of a forward propagation and feeding this loss backward through the neural network layers to fine-tune the weights. Backpropagation is the essence of neural net training.

## Topological sort 
&rarr;  Topological sort is an algorithm that sorts a directed acyclic graph (DAG) by returning an array or a vector that consists of nodes where each node appears before all the nodes it points to. In other words, it is a linear ordering of vertices such that for every directed edge u -> v, vertex u comes before v in the ordering

![Topological sort](https://i.ytimg.com/vi/rSCR8r2aNA8/maxresdefault.jpg)

```
topo = []
visited = set()

def build_topo(v):
    if v not in visited:
        visited.add(v)
        for child in v._prev:
            build_topo(child)
        topo.append(v)
build_topo(o)

```