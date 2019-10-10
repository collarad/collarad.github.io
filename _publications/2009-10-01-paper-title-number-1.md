---
title: "MINTE: semantically integrating RDF graphs"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'This paper is about semantically integrating heterogeneous data sources.'
date: 2017-06-01
venue: 'WIMS'17'
paperurl: 'http://collarad.github.io/files/paper1.pdf'
citation: 'Diego Collarana, Mikhail Galkin, Ignacio Traverso Ribón, Maria-Esther Vidal, Christoph Lange, Sören Auer: MINTE: semantically integrating RDF graphs. WIMS 2017: 22:1-22:11'
---
The nature of the RDF data model allows for numerous descriptions of the same entity. For example, different RDF vocabularies may be utilized to describe pharmacogenomic data, and the same drug or gene is represented by different RDF graphs in DBpedia or Drug-bank. To provide a unified representation of the same real-world entity, RDF graphs need to be semantically integrated. Semantic integration requires the management of knowledge encoded in RDF vocabularies to determine the relatedness of different RDF representations of the same entity, e.g., axiomatic definition of vocabulary properties or resource equivalences. We devise MINTE, an integration technique that relies on both: knowledge stated in RDF vocabularies and semantic similarity measures to merge semantically equivalent RDF graphs, i.e., graphs corresponding to the same real-world entity. MINTE follows a two-fold approach to solve the problem of integrating RDF graphs. In the first step, MINTE implements a 1--1 weighted perfect matching algorithm to identify semantically equivalent RDF entities in different graphs. Then, MINTE relies on different fusion policies to merge triples from these semantically equivalent RDF entities. We empirically evaluate the performance of MINTE on data from DBpedia, Wiki-data, and Drugbank. The experimental results suggest that MINTE is able to accurately integrate semantically equivalent RDF graphs.

[Download paper here](http://collarad.github.io/files/paper1.pdf)

Recommended citation: Diego Collarana, Mikhail Galkin, Ignacio Traverso Ribón, Maria-Esther Vidal, Christoph Lange, Sören Auer: MINTE: semantically integrating RDF graphs. WIMS 2017: 22:1-22:11.