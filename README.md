# Welcome AI Overlords Paper Reading Group 

## Paper 1 - GraphWorld: Fake Graphs Bring Real Insights for GNNs

### Link to the paper - [https://arxiv.org/abs/2203.00112]

### Date of Presentation - 13th May 2022

### Name of Presenter - Zak Jost 

### Paper Summary - 

The GraphWorld paper argues that datasets used for benchmarking Graph Neural Networks have properties that represent a narrow slice of possible graph structures and the community can therefore be led astray by only using these benchmarks to evaluate methods.  To solve this problem, they build a framework for creating populations of synthetic graphs with a wide set of properties and methods to efficiently search this space, and argue this is a better way to benchmark GNNs.  Their results and insights are limited, however, by their choices of which properties describe meaningfully different graphs, and the details of their synthetic graph generation processes.  No attempt is made to show that rankings of GNN methods on synthetic graphs carry over to real-life graphs that occupy the same region of their graph property space, so it's unclear whether results on synthetic graphs have a meaningful connection to real graphs.


## Paper 2 - Inside the Atoms: Ranking on a Network of Networks

### Link to the paper - [http://tonghanghang.org/pdfs/kdd14_non.pdf]

### Date of Presentation - 17th June 2022

### Name of Presenter - Wondi

### Paper Summary - 

A network of networks is a network where all the nodes in the main network have a network (called a domain-specific network). With this network, the authors of this paper have solved interesting problems such as ranking all the nodes based on their local popularity within the domain specific network and the global popularity of their corresponding domain, or finding similar nodes to a query node. The structure of their network of networks allows them to increase the accuracy of their results.
