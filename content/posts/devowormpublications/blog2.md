+++
title =  "Learning on Graphs (LoG) conference recap"
tags = ["DevoWorm", "Bradly Alicea"]
date = "2022-12-23"
+++





<p align="center">
<img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhBDFSrY1N8XSby52rvFfhB6i7rLtM6SobdfKoIGb5fJt2RY2Mw3ysdsbDX5Vz4lKIJ_UFlskZRsOPqTjCICpIyP4aE7_2PaJsk9TiqlxEzJCEfTsJxEzGAgWFLIbfKZee-via77dTJesFnxep1sD8NW20RiQzcRUi90LWihNFXH3KknJJDl_gmaZal/w200-h200/logo_conf_below_512_512_hu0b3b5122a793f6cbe7d94790c745769e_24489_400x0_resize_lanczos_3.png" alt='Darwin Image'/>
</p>

The [Learning on Graphs (LoG)](https://logconference.org/) conference took place from December 9-12 and featured a broad diversity of research on [Graph Neural Networks (GNNs)](https://en.wikipedia.org/wiki/Graph_neural_network). GNNs [1] encompass a relatively new area of machine learning research which have a number of interesting connections to applied math and network science. The daily sessions (keynote talks and oral presentations), in addition to the seven workshop sessions, are available from the conference [YouTube channel](https://www.youtube.com/@learningongraphs).

GNNs are a way to take data that yield graphical relationships in the real world and analyze then using the power of neural networks. While GNNs are specialized for problems that can be represented as a graph (discrete, interconnected systems), any problem with a set of complex geometric relationships is appropriate for GNNs. While the output of GNNs are typically [embeddings](https://en.wikipedia.org/wiki/Embedding) (graph topologies embedded in the feature space), some problems require different approaches such as functions or more formal representations. 

It is the analysis of these graphical relationships which make it a useful analytical approach. In all their forms, GNNs yield useful representations of graph data partly because they take into consideration the intrinsic symmetries of graphs, such as [invariance](https://en.wikipedia.org/wiki/Invariant_(physics)) and [equivariance](https://en.wikipedia.org/wiki/Equivariant_map) of graph topology with respect to a relabeling of the nodes [2]. Based on what was featured at LoG, GNNs had many potential applications in the biological arena, including precision medicine, drug discovery, and characterizing molecular systems (such as [Stefan Gunnemann's (Technical University of Munich)](https://scholar.google.de/citations?user=npqoAWwAAAAJ&hl=en) talk in the [Friday session](https://www.youtube.com/watch?v=wp5S9GHyAgw)).

<p align="center">
  <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgkVIvb3bNN2VI31hX9rTo2GKwTr5DMZtM-Q5GLAmSLoiGwlN4z6Q_hOb3DwsIxeo5ncFOfafu1eABO4D0tGjlGAmexB2cR9oQhHj-CY9uVNqs_CdigYmh_WlH-iL-VVQ9muVsOuAOJigCruiIrmIbOGoli3GLcCoRXEj2QwqXCffqmUm2yAnU-WtnW/w400-h225/Screenshot%202022-12-23%20at%201.00.14%20PM.png" alt="Sublime's custom image"/>
</p>

GNNs can be evaluated using the [isomorphism (or k-WL)](https://en.wikipedia.org/wiki/Graph_isomorphism_problem) test, which evaluates whether two graphs are isomorphic. Given that a graph can be drawn from the source data, the source data graph should be isomorphic with the output graph. The [Weisfeiler-Lehman heuristic for graph isomorphism](https://towardsdatascience.com/expressive-power-of-graph-neural-networks-and-the-weisefeiler-lehman-test-b883db3c7c49) can be summarized in the 1-D case as the [color refinement algorithm](https://en.wikipedia.org/wiki/Colour_refinement_algorithm). A related issue in GNN research is algorithmic expressiveness. Expressivity is the breadth of ideas that can be represented and communicated using a particular type of representation. One current challenge of GNNs as they are applied to various problem domains is their ability to be functionally robust. One solution to this is by using GNNs as a generative model. Generating alternate graph representations allows us to use [graphons](https://en.wikipedia.org/wiki/Graphon) [3], functions that capture different GNN topologies of the same type. The collection of graphs associated with a graphon can then be evaluated. [Soledad Villar's (Johns Hopkins)](https://scholar.google.com/citations?user=JBGlsDoAAAAJ&hl=en) presentation during the [Sunday session](https://www.youtube.com/watch?v=wp5S9GHyAgw) featured an in-depth discussions of expressiveness and graphons as they relate to GNN performance.

<p align="center">
  <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEi2pupjPwNwMfkTc3ihXKCQ-5_Umnr-UzIrcmXjChdOTsb_8WCEUCo2ag-81JHYyST_5hTNdPoem6cQEV0xleOwc4yQS5nfqWcWs2YWROTHERjWr4QMC_Obe4i632Ru0gE0ThdQXWg2ZMwbQoXkx7LDDS_Y6agQ2n_G_nomI5sS83z5L_jgTqYP9zx6/w400-h225/Screenshot%202022-12-23%20at%2012.50.12%20PM.png" alt="Sublime's custom image"/>
</p>

GNNs can be combined with various analytical techniques traditionally used in [complex network](https://en.wikipedia.org/wiki/Complex_network) analysis. One of these involves the analysis of graphical models using tools from network science. These include the use of [random graphs](https://en.wikipedia.org/wiki/Random_graph) and [stochastic block models](https://en.wikipedia.org/wiki/Stochastic_block_model) to uncover the presence of topological structure and community formation, respectively. GNNs have ties to [category theory](https://en.wikipedia.org/wiki/Category_theory) as well. The [cats.for.ai](http://cats.for.ai/) workshop (October 2022) featured applications of category theory to GNNs. In the Saturday session, [Taco Cohen (Qualcomm AI)](https://scholar.google.com/citations?user=a3q4YxEAAAAJ) discussed how the techniques of category theory, [monads](https://en.wikipedia.org/wiki/Monad_(functional_programming)) in particular, can be applied to GNNs. GNNs can also form [directed acyclic graphs (DAGs)](https://en.wikipedia.org/wiki/Directed_acyclic_graph), which are amenable to causal models. 

<p align="center">
  <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjuf89qismqqOLTVVdSTiiYUNJoDUdYumwie3EbXivS5LP2hiy0kfElObWrs5bUTx1saEF7p6plcMqS8myUw2eS22xcz-vC0X1ROOlA_b81JUo7YpjQd1rJ0SvcWgpiPT1mxVv0IBXen2NOTdBpEPT5s38AorkPpZkwhAcoNR02Sr83qqsFFvgvDYNv/w400-h225/Screenshot%202022-12-23%20at%2012.53.55%20PM.png" alt="Sublime's custom image"/>
</p>

GNNs are constructed using a series of inferential techniques. One technique discussed at LoG is [message passing](https://en.wikipedia.org/wiki/Message_passing) neural networks (MPNNs). Discrete forward passes from node to node (along edges) allow for approximation of the true, original network topology to be reconstructed. MPNN is a standard technique that lends itself to a wide variety of problem domains. The MPNN approach [4] can be extended to directed [multigraphs](https://en.wikipedia.org/wiki/Multigraph) and other types of graphs that capture complex systems, but can suffer shortcomings such as over-smoothing, over-squashing and under-reaching. While message passing has been the standard in the GNN field, continuous methods using approaches inspired by differential geometry and algebraic topology might serve as powerful alternatives [5]. Aside from approximations of real-world networks and graph-like structures, we can also think of GNN outputs in terms of time (capturing delays) and space (capturing translations). GNNs are also well-suited to mapping problems from algorithmic domains, in particular dynamic programming [6].



GNNs are particularly useful for task-specific architectures. The [DevoWorm](https://devoworm.weebly.com/) group’s [D-GNN work (DevoGraph)](https://github.com/DevoLearn/DevoGraph) is an example of this, being specialized for embryogenetic image processing or capturing biological growth and differentiation processes. But GNNs can also engage in transfer learning, which is the transfer of learned information from one context to another. Successful graph transfer learning is characterized by the reproduction of a graph of a similar but different size, or problems that require changes in network size over time.


<p align="center">
  <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEiL_CCN5O5PphG2WcRVAoomaOFFwRB7ntpfZHGJg4VNNwgy97FwSxhynWI7PSLBv-ZVypVyswoWV0okcZdlEgMjvz2edkqIX0BDnBWIslKtx6n3VeeSSXz_BnO2A_5ShVCeDPS1_tenj47Uc7ngwFXtAlCV7g__hzBg3v0fTdNQL6QP11Ll3LDIvDBM/w400-h170/1_CWUg-DZBQNONJXuxQdLrFQ.png" alt="Sublime's custom image"/>
</p>

From ["Do we need deep graph neural networks?"](https://towardsdatascience.com/do-we-need-deep-graph-neural-networks-be62d3ec5c59) by Michael Bronstein, Towards Data Science, July 20, 2020.



Workshops

Several of the workshops were particularly interesting with respect to some of the points mentioned above. There were also a number of outstanding [oral presentations](https://logconference.org/schedule-orals/) and [posters](https://logconference.org/schedule-posters/) not discussed here, but are worth checking out in the [daily session recordings](https://www.youtube.com/@learningongraphs/streams) or on [OpenReview](https://openreview.net/group?id=logconference.io/LOG/2022/Conference).



Neural Algorithmic Reasoning ([video](https://www.youtube.com/watch?v=SKQ96tDZhgw)). GNNs serve as excellent processors (neural networks in latent space) that can be aligned with more traditional algorithms [7]. This recasts many optimization problems as neural representation learning, particularly in cases where optimization algorithms do not represent the system being analyzed in a realistic manner.

<p align="center">
  <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgAFXdR6wlDJ3fPftFEMaTHPFydKUBg-EmgrVQ19r1l-5sGvYebboq7NXJvYTk26n33k-ooXB9LBsuPX80XUGQuOyflPMw5q8d8tf0ovRtYQnraMsx_TYiCavLYONuxALqMZgR_U9fXarwjz4HO2VUCZ7nmL7fZRR9VYdgmt9pW3VJfZ1ePmFl2N87u/w400-h225/Screenshot%202022-12-23%20at%201.01.04%20PM.png" alt="Sublime's custom image"/>
</p>


Expressive GNNs ([video](https://www.youtube.com/watch?v=ASQYjbUBYzs)). This tutorial covers a range of techniques that can be used to increase the expressivity of GNNs. Borrowing from areas such as topological data analysis and group theory, there is great potential for a variety of highly effective strategies for improving GNN architectures for a host of problems.



Graph Rewiring ([video](https://www.youtube.com/watch?v=AumdG5bazhg), [web](https://ellisalicante.org/tutorials/GraphRewiring)). Graph rewiring is presented as a way to overcome the limitations of the MPNN approach. Rewiring is based on the reconstruction of graph edges from iterative adaptive sampling of the input data. There are a number of different techniques that allow us to evaluate edge relevance using techniques such as diffusion and spectral approaches.



GNNs on TensorFlow ([video](https://www.youtube.com/watch?v=JqWROPYeqjA)). This tutorial introduces nascent modelers to implementing their own GNN models in the open-source [TF-GNN framework](https://github.com/tensorflow/gnn). The tutorial uses heterogeneous input data to show how to implement the GNN and deal with missing label and edge information. 



## References

[1] Sanchez-Lengeling, B., Reif, E., Pearce, A., and Wiltschko, A.B. (2021). [A Gentle Introduction to Graph Neural Networks. Distill](https://distill.pub/2021/gnn-intro/), doi:10.23915/distill.00033.



[2] Chen, Z., Villar, S., Chen, L., and Bruna, J. (2019). [On the equivalence between graph isomorphism testing and function approximation with GNNs. Proceedings of Neural Information Processing Systems](https://papers.nips.cc/paper/2019/hash/71ee911dd06428a96c143a0b135041a4-Abstract.html), 32.

[3] Ruiz, L., Chamon, L.F.O., and Ribeiro, A. (2020). [Graphon Neural Networks and the Transferability of Graph Neural Networks](https://arxiv.org/abs/2006.03548). arXiv, 2006.03548.

[4] Heydari, S. and Livi, L. (2022). [Message Passing Neural Networks for Hypergraphs](https://arxiv.org/abs/2203.16995v2). arXiv, 2203. 16995.

[5] Bronstein, M. (2022). [Beyond Message Passing: a Physics-Inspired Paradigm for Graph Neural Networks](https://thegradient.pub/graph-neural-networks-beyond-message-passing-and-weisfeiler-lehman/). The Gradient, May 7.

[6] Dudzik, A. and Velickovic, P. (2022). [Graph Neural Networks are Dynamic Programmers](https://arxiv.org/abs/2203.15544). arXiv, 2203.15544.

[7] Velickovic, P. and Blundell, C. (2021). [Neural Algorithmic Reasoning](https://arxiv.org/abs/2105.02761). arXiv, 2105.02761.

Posted by [Bradly Alicea](https://www.linkedin.com/in/bradlyalicea/) 
