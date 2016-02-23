---
layout: post
title:  "First release of the tool to group HUMAnN2 UniRef50 abundances into Gene Ontology (GO) slim terms"
date:   2016-02-22 22:40
categories: blog
---

The [first release](https://github.com/ASaiM/group_humann2_uniref_abundances_to_GO/releases/tag/v1.0.0) of the tool to group HUMAnN2 UniRef50 abundances into Gene Ontology (GO) slim terms is available. This first release of `group_humann2_uniref_abundances_to_GO` is associated to a [DOI](https://zenodo.org/badge/latestdoi/19862/ASaiM/group_humann2_uniref_abundances_to_GO).

[HUMAnN2](http://huttenhower.sph.harvard.edu/humann2) is a pipeline to profile the presence/absence and abundance of microbial pathways in community of microbiota sequencing data. One output is a file with UniRef50 gene family abundances. However, these gene families are too precise. To get global categories from HUMAnN2 outputs, [Gene Ontology](http://geneontology.org/) can be used. Gene ontology project is a collaborative project to get a 3 structures ontologies to describe gene products in terms of their associated biological processes, cellular components and molecular functions. 

HUMAnN2 gives opportunity to regroup UniRef50 gene family abundances into GO abundances. However, these GO terms are still too precise to get a good overview of metabolic processes. Alternatively, Gene Ontology Consortium proposes [GO slim](http://geneontology.org/page/go-slim-and-subset-guide), which are cut-down versions of the GO ontologies to give a broad overview of the ontology content. For microbiota analysis, metagenomic GO slim terms developed by Jane Lomax and the InterPro group are used.

The tool [`group_humann2_uniref_abundances_to_GO`](https://github.com/ASaiM/group_humann2_uniref_abundances_to_GO) regroup HUMAnN2 output containing UniRef50 gene family abundances into abundances of metagenomic GO slim term. This tool uses [GoaTools](https://github.com/tanghaibao/goatools) to map GO terms to GO slim terms, HUMAnN2 to regroup abundances of UniRref50 gene families into abundances of metagenomc GO slim terms and custom Python scripts.

This tool can be used by itself (in command line), but it is alos associated with a wrapper for Galaxy. This wrapper is currently available on Galaxy Test ToolShed under name `group_humann2_uniref_abundances_to_go`, with owner bebatut. It can then be installed on every Galaxy instance.