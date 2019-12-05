# Epidemic Graph Convolutional Network

#### Authors: [Tyler Derr](http://www.TylerDerr.com) (derrtyle@msu.edu), [Yao Ma](http://www.http://cse.msu.edu/~mayao4/) (mayao4@msu.edu), [Wenqi Fan](https://wenqifan03.github.io/) (wenqifan03@gmail.com), [Xiaorui Liu](http://www.http://cse.msu.edu/~xiaorui/) (xiaorui@msu.edu), [Charu Aggarwal](http://charuaggarwal.net/) (charu@us.ibm.com), and [Jiliang Tang](http://www.cse.msu.edu/~tangjili) (tangjli@msu.edu)

<div style="text-align:center"><img src ="framework.png" ,width=400/></div>

### Abstract

A growing trend recently is to harness the structure of today's big data, where much of the data can be represented as graphs. Simultaneously, graph convolutional networks (GCNs) have been proposed and since seen rapid development. More recently, due to the scalability issues that arise when attempting to utilize these powerful models on real-world data, methodologies have sought the use of sampling techniques. More specifically, minibatches of nodes are formed and then sets of nodes are sampled to aggregate from in one or more layers. Among these methods, the two prominent ways are based on sampling nodes from either a local or global perspective. In this work, we first observe the similarities in the two sampling strategies to that of epidemic and diffusion network models. Then we harness this understanding to fuse together the benefits of sampling from both a local and global perspective while alleviating some of the inherent issues found in both through the use of a low-dimensional approximation for the path-based Katz similarity measure. Our proposed framework, Epidemic Graph Convolutional Network (EGCN), is thus able to achieve improved performance over sampling from just one of the two perspectives alone. Empirical experiments are performed on several public benchmark datasets to verify the effectiveness over existing methodologies for the node classification task and we furthermore present some empirical parameter analysis of EGCN.

If you make use of this code in your work, please cite the following paper:

    @inproceedings{derr2020epidemic,
     author = {Derr, Tyler and Ma, Yao and Fan, Wenqi and Liu, Xiaorui and Aggarwal, Charu and Tang, Jiliang},
     title = {Epidemic Graph Convolutional Network},
     booktitle = {In Proceedings of the 13th ACM International Conference on Web Search and Data Mining (WSDM)},
     year = {2020}
     publisher = {ACM}
    } 

## Code and preprint coming soon!
