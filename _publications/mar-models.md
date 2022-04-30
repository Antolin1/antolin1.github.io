---
title: "MAR: a structure-based search engine for models"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'This paper is about a search engine for models.'
date: 2020-10-01
venue: '23rd ACM/IEEE International Conference on Model Driven Engineering Languages and Systems'
paperurl: 'https://arxiv.org/pdf/2008.11858.pdf'
citation: 
---

The availability of shared software models provides opportunities
for reusing, adapting and learning from them. Public models are
typically stored in a variety of locations, including model repositories, regular source code repositories, web pages, etc. To profit
from them developers need effective search mechanisms to locate
the models relevant for their tasks. However, to date, there has
been little success in creating a generic and efficient search engine
specially tailored to the modelling domain.
In this paper we present MAR, a search engine for models. MAR
is generic in the sense that it can index any type of model if its metamodel is known. MAR uses a query-by-example approach, that is, it
uses example models as queries. The search takes the model structure into account using the notion of bag of paths, which encodes
the structure of a model using paths between model elements and
is a representation amenable for indexing. MAR is built over HBase
using a specific design to deal with large repositories. Our benchmarks show that the engine is efficient and has fast response times
in most cases. We have also evaluated the precision of the search
engine by creating model mutants which simulate user queries. A
REST API is available to perform queries and an Eclipse plug-in
allows end users to connect to the search engine from model editors.
We have currently indexed more than 50.000 models of different
kinds, including Ecore meta-models, BPMN diagrams and UML
models. MAR is available at [http://mar-search.org](http://mar-search.org).

[Download paper here](https://arxiv.org/pdf/2008.11858.pdf)
