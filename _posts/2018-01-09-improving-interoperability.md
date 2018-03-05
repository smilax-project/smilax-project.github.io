---
layout: post
title: Improving the interoperability of biomedical ontologies with compound alignments
tags: [ontology matching, biomedical ontologies, semantic networks, interoperability]
excerpt_separator: <!--more-->
---

Our new [paper](https://jbiomedsem.biomedcentral.com/articles/10.1186/s13326-017-0171-8) on Journal of Biomedical Semantics is out. 

<!--more-->

### Background

Ontologies are commonly used to annotate and help process life sciences data. Although their original goal is to facilitate integration and interoperability among heterogeneous data sources, when these sources are annotated with distinct ontologies, bridging this gap can be challenging. In the last decade, ontology matching systems have been evolving and are now capable of producing high-quality mappings for life sciences ontologies, usually limited to the equivalence between two ontologies. However, life sciences research is becoming increasingly transdisciplinary and integrative, fostering the need to develop matching strategies that are able to handle multiple ontologies and more complex relations between their concepts.

### Results

We have developed ontology matching algorithms that are able to find compound mappings between multiple biomedical ontologies, in the form of ternary mappings, finding for instance that “aortic valve stenosis”(HP:0001650) is equivalent to the intersection between “aortic valve”(FMA:7236) and “constricted” (PATO:0001847). The algorithms take advantage of search space filtering based on partial mappings between ontology pairs, to be able to handle the increased computational demands. The evaluation of the algorithms has shown that they are able to produce meaningful results, with precision in the range of 60-92% for new mappings. The algorithms were also applied to the potential extension of logical definitions of the OBO and the matching of several plant-related ontologies.

### Conclusions

This work is a first step towards finding more complex relations between multiple ontologies. The evaluation shows that the results produced are significant and that the algorithms could satisfy specific integration needs.

