---
layout: post
title: Tackling the challenges of matching biomedical ontologies
tags: [ontology matching, biomedical ontologies, semantic networks]
excerpt_separator: <!--more-->
---

Another new [paper](https://jbiomedsem.biomedcentral.com/articles/10.1186/s13326-017-0170-9) on Journal of Biomedical Semantics. 

<!--more-->
### Background

Biomedical ontologies pose several challenges to ontology matching due both to the complexity of the biomedical domain and to the characteristics of the ontologies themselves. The biomedical tracks in the Ontology Matching Evaluation Initiative (OAEI) have spurred the development of matching systems able to tackle these challenges, and benchmarked their general performance. In this study, we dissect the strategies employed by matching systems to tackle the challenges of matching biomedical ontologies and gauge the impact of the challenges themselves on matching performance, using the AgreementMakerLight (AML) system as the platform for this study.

### Results

We demonstrate that the linear complexity of the hash-based searching strategy implemented by most state-of-the-art ontology matching systems is essential for matching large biomedical ontologies efficiently. We show that accounting for all lexical annotations (e.g., labels and synonyms) in biomedical ontologies leads to a substantial improvement in F-measure over using only the primary name, and that accounting for the reliability of different types of annotations generally also leads to a marked improvement. Finally, we show that cross-references are a reliable source of information and that, when using biomedical ontologies as background knowledge, it is generally more reliable to use them as mediators than to perform lexical expansion.

### Conclusions

We anticipate that translating traditional matching algorithms to the hash-based searching paradigm will be a critical direction for the future development of the field. Improving the evaluation carried out in the biomedical tracks of the OAEI will also be important, as without proper reference alignments there is only so much that can be ascertained about matching systems or strategies. Nevertheless, it is clear that, to tackle the various challenges posed by biomedical ontologies, ontology matching systems must be able to efficiently combine multiple strategies into a mature matching approach.

