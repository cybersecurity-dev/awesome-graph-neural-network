```mermaid
timeline
    title Evolution of Graph Neural Network Methods
    2005 : Early graph neural network formulation
    2009 : The Graph Neural Network Model
    2013-2014 : Spectral graph convolution foundations
              : DeepWalk-era graph representation learning
    2016 : ChebNet
         : Gated Graph Neural Networks
         : GCN preprint
    2017 : GCN conference publication
         : Neural Message Passing framework
         : GraphSAGE
         : GAT preprint
    2018 : GAT conference publication
         : R-GCN
         : DGCNN and SortPooling
         : FastGCN
    2019 : GIN
         : Deep Graph Infomax
         : APPNP
         : Cluster-GCN
         : GraphSAINT
         : SAGPool
    2020 : GCNII
         : GraphCL
         : H2GCN
         : EvolveGCN
    2021 : Graphormer
         : GATv2
         : GraphGPS direction emerges
    2022-2024 : Local-global graph transformers
              : Heterophily-aware GNNs
              : Graph foundation and diffusion models

```

# Awesome Graph Neural Network ([**GNN**](https://wikipedia.org/wiki/Graph_neural_network))
</div>

[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)]() 
[![Reddit](https://img.shields.io/badge/Reddit-FF4500?style=for-the-badge&logo=reddit&logoColor=white)](https://www.reddit.com/r/LanguageTechnology/new/)

<p align="center">
    <a href="https://github.com/cybersecurity-dev/"><img height="25" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/github.svg" alt="GitHub"></a>
    &nbsp;
    <a href="https://www.youtube.com/@CyberThreatDefense"><img height="25" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/youtube.svg" alt="YouTube"></a>
    &nbsp;
    <a href="https://cyberthreatdefence.com/my_awesome_lists"><img height="20" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/blog.svg" alt="My Awesome Lists"></a>
    <img src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/bar.gif">
</p>

```mermaid
flowchart LR
    GNN["GNN<br/>General framework"] --> MP["Message Passing"]

    MP --> GCN["GCN"]
    MP --> GAT["GAT"]

    GCN --> GCNA["Uses normalized<br/>adjacency weights"]
    GAT --> GATA["Learns attention<br/>weights"]

    GCNA --> GCNF["All connected neighbors<br/>contribute according to degree"]
    GATA --> GATF["Important neighbors can<br/>contribute more"]

    GCNF --> OUT["Node or Graph Embedding"]
    GATF --> OUT

    classDef general fill:#ede7f6,stroke:#5e35b1,stroke-width:2px,color:#000
    classDef gcn fill:#e8f5e9,stroke:#2e7d32,stroke-width:2px,color:#000
    classDef gat fill:#fff3e0,stroke:#ef6c00,stroke-width:2px,color:#000
    classDef output fill:#e3f2fd,stroke:#1565c0,stroke-width:2px,color:#000

    class GNN,MP general
    class GCN,GCNA,GCNF gcn
    class GAT,GATA,GATF gat
    class OUT output
```

## 📖 Contents
- [My Other Awesome Lists](#my-other-awesome-lists)
- [Contributing](#contributing)
- [Contributors](#contributors)
- 
##

### My Other Awesome Lists
You can access the my other awesome lists [here](https://cyberthreatdefence.com/my_awesome_lists)

### Contributing
[Contributions of any kind welcome, just follow the guidelines](contributing.md)!

### Contributors
[Thanks goes to these contributors](https://github.com/cybersecurity-dev/awesome-graph-neural-network/graphs/contributors)!

### License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

[🔼 Back to top](#awesome-graph-neural-network-gnn)
