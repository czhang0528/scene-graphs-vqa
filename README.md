# Leveraging Scene Graphs for Visual QA

Tensorflow code for our BMVC 2019 paper 
"[An Empirical Study on Leveraging Scene Graphs for Visual Question Answering](https://arxiv.org/abs/1907.12133)"

![](figures/framework.png)

We will release the code and data soon.

## Introduction
We investigate the use of scene graphs (SGs) derived from images for visual question answering (Visual QA): an image is abstractly represented by a graph 
with nodes corresponding to object entities and edges to object relationships. We adapt the recently proposed 
graph networks (GNs) to encode the scene graph and perform structured reasoning according to the input question. 
Our empirical studies demonstrate that scene graphs can already capture essential information of images and graph 
networks have the potential to outperform state-of-the-art Visual QA algorithms but with a much cleaner architecture. 
By analyzing the features generated by GNs we can further interpret the reasoning process, suggesting a promising 
direction towards explainable Visual QA.

## Citation
Please cite with the following bibtex if you find it useful.
```
@inproceedings{zhang2019empirical,
  title={An Empirical Study on Leveraging Scene Graphs for Visual Question Answering},
  author={Zhang, Cheng and Chao, Wei-Lun and Xuan, Dong},
  booktitle={British Machine Vision Conference (BMVC)},
  year={2019}
}
```

<!-- ## Acknowledgement

Part of the code uses components from [Deepmind Graph Nets library](https://github.com/deepmind/graph_nets). 
We thank authors for releasing their code. -->

