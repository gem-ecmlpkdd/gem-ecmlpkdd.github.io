---
layout: page
title: "Tutorial: Hands-On Graph Analysis with scikit-network"
permalink: /tutorial/
---
---


### Abstract
The objective of the tutorial is to familiarize the audience with scikit-network, a recent Python library for graph analysis. Inspired by scikit-learn, the package provides state-of-the-art algorithms for ranking, clustering, classifying, embedding and visualizing the nodes of a graph. High performance is achieved through a mix of fast matrix-vector products (using SciPy), compiled code (using Cython) and parallel processing. 
Description of the tutorial

Graphs of various types, such as plain networks, linked/semantic web/RDF data, attributed, dynamic, interaction graphs, and possibly combinations of these, are increasingly used as versatile and practical models for data encountered in today’s data-intensive research and industries. In contrast to data tables, graphs allow capturing the information about entities (using attributes or properties), as well as the relational structure between entities. The ability to discover knowledge from and make predictions about such network data has gained in importance quickly. However, the scale of such real-world data, with network sizes typically ranging in the millions of nodes, requires efficient data structures and libraries, and algorithmic trade-offs that are different from the most general case, implemented for example in libraries such as networkx. This is exactly what scikit-network is intended for: a Python library running efficiently on large graphs, following the now common scikit-learn API.

The objective of the tutorial is to familiarize the audience with scikit-network. After an introduction to the core components of the library, the participants will work on a real-world use case combining graph and text mining.

The tutorial will consist of two sessions, separated by a break. The first session (1h30) will cover the basics of scikit-network, including the data structure (sparse matrices in CSR format) and the main clustering, embedding and ranking methods. The second session (1h) will focus on a real-world use case, namely the analysis of Wikipedia through both its hyperlinks and texts. Time will be left at the end (around 15 min) to present the different ways to contribute to the library, and open the discussion.
Relevance to the ECML-PKDD community

Arguments over the prevalence of networks in current datasets and the necessity of a community gathering at ECML-PKDD have already been given in the workshop section of this document. Let us add here that in this community, there is a critical need of libraries that are targeted towards researchers, and towards the handling of large scale datasets. Of course, libraries filling this space already exist; for example, Networkx and Graphml for classical graph analysis, and pytorch-geometric and the Deep Graph Library for deep learning on graphs. To the best of our knowledge, scikit-network is the only non-deep learning focused graph Python library that is able to run fast on very large graphs with minimal memory footprint. As such, we believe that introducing scikit-network to a wider audience will help fill the current space in the research practices for graph analysis and machine learning on sparse data.

The tutorial targets anyone interested in the analysis of large real-world graphs, including data scientists, engineers and researchers. Core researchers may be interested by the internal mechanics of the library, and how they allow scaling. Applied researchers may be interested by the breadth of algorithms already implemented in the library that are usable straightforwardly. Both may also discover new tools to analyze their data and extract insight from it. Participants will benefit from having a technical background, a familiarity with Python, and a basic understanding of graphs. The GEM workshop audience is at the core of the target audience of this tutorial.
Tutorial structure

**Session 1: Introduction and core components (1h30)**
- Installation
- The Compressed Sparse Row format
- Loading data
- PageRank
- Clustering
- Embedding

**Break**

**Session 2: Real-world use case (1h)**
- Scikit-network applied to graph and text mining: analysis of Wikipedia.
	
**Session 3: Concluding remarks (15’)**
- How to contribute (github, issues, wiki)
- Further questions and discussion from the audience

### Tutorial instructors
**Thomas Bonald** is a Professor at Institut Polytechnique de Paris, France. He is one of the founders and active developers of scikit-network. His current research interests are in graph analysis, NLP and knowledge bases.

**Tiphaine Viard** is an associate professor at Institut Polytechnique de Paris, France. She is part of scikit-network’s development team. Her research interests focus on at the intersection of large complex network analysis (including their extensions : dynamic, multilayer, attributed networks) and machine learning.

### Technical requirements
Jupyter notebook with Python3
