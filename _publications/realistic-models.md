---
title: "Towards the Characterization of Realistic Model Generators using Graph Neural Networks"
collection: publications
permalink: /publication/realistic-models
excerpt: 'This paper is about using GNNs to assess realism in model generators.'
date: 2021-10-10
venue: '24rd ACM/IEEE International Conference on Model Driven Engineering Languages and Systems'
paperurl: 'http://sanchezcuadrado.es/papers/models21-realistic-model-generators.pdf'
citation: 
---

**Abstract:** The automatic generation of software models is an
important element in many software and systems engineering
scenarios such as software tool certification, validation of cyber-physical systems, 
or benchmarking graph databases. Several
model generators are nowadays available, but the topic of
whether they generate realistic models has been little studied.
The state-of-the-art approach to check the realistic property in
software models is to rely on simple comparisons using graph
metrics and statistics. This generates a bottleneck due to the
compression of all the information contained in the model into a
small set of metrics. Furthermore, there is a lack of interpretation
in these approaches since there are no hints of why the generated
models are not realistic. Therefore, in this paper, we tackle the
problem of assessing how realistic a generator is by mapping it to
a classification problem in which a Graph Neural Network (GNN)
will be trained to distinguish between the two sets of models (real
and synthetic ones). Then, to assess how realistic a generator is we
perform the Classifier Two-Sample Test (C2ST). Our approach
allows for interpretation of the results by inspecting the attention
layer of the GNN. We use our approach to assess four state 
of-the-art model generators applied to three different domains.
The results show that none of the generators can be considered
realistic.

[Download paper here](http://sanchezcuadrado.es/papers/models21-realistic-model-generators.pdf)
