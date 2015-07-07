---
layout: page
title: About
---

## Why ASaiM?

Numerous tools are currently available to process and analyze metagenomics
sequences (MG-Rast, Galaxy, MEGAN, QIIME, etc) However, they are often
difficult to use, not adjustable, only one step in sequence processing, ... And
currently, none can integrate metagenomics and metatranscriptomic information
processing.

Public databases are overflowing with intestinal microbiota information.
However, this information is generally buried in these databases and difficult
to interrogate (may databases to interrogate, few metadata, ...).

To bring some solution to these issues, we are developping _Auvergne Sequence
Analysis of Intestinal Microbiota_ (ASaiM), an environment to analyze
metagenomic and metatranscriptomic sequences from intestinal microbiota.

## What is ASaiM exactly?

The ASaiM environment is constituted of two "objects".

This first object is an expert database combining information from analysis of
intestinal microbiota that can be found on public databases and from our
analyses. This database is developed to be data sources and facilitate analyses
such as comparative metagenomics or metatranscriptomics. However, this database
is currently under construction.

The second object is a framework to process and analyze intestinal microbiota
from raw sequences to taxonomic and functional assignations. In this framework,
several tools and databases are available. They are tools for metagenomics and
metatranscriptomics sequences and are generally devoted to one step in the
treatments to do to these data. So, the framework is here to help the users to
choose the tools and parameters and then design a pipeline to process the
sequences. Moreover, the framework provides an environment to execute the
designed pipeline without to have to install all the wanted tools and their
dependencies. The framework is then developped in the philosophy to be:

- easy to use for all from beginners to expert, with an help in pipeline
  design, a minimalist execution environment, an heavy [documentation]({{ site.documentation_page }}), ...
- adjustable with numerous proposed tools and parameters

This framework is a tool to process the available data about intestinal
microbiota and supply the database with standardized information.

## Who is involved?

The project is founded by a CPER Auvergne contract and involved multiple
partners:

 * [EA 4678 - CIDAM](http://www.u-clermont1.fr/cidam.html)
 * [UR 454 - Microbio](http://www6.clermont.inra.fr/microbiologie)
 * [UMR 1213 – Unité mixte de recherche sur les herbivores (UMRH)](http://www1.clermont.inra.fr/urh/)
 * [M2iSH – UMR 1071 Inserm / UdA / USC 2018 INRA](http://www.u-clermont1.fr/m2ish.html)
 * [LIMOS – UMR CNRS 6158 / UBP / /UdA ](http://limos.isima.fr/)
 * [TailorDev](http://tailordev.fr/)
 * [CRRI](https://crri.clermont-universite.fr/)
