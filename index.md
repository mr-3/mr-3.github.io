---
layout: home_page
permalink: /index.html
---

# What’s New
* 2025-03-16: MR<sup>3</sup> 25.3.1 Released.
* 2024-05-06: MR<sup>3</sup> 24.5.1 Released.
* 2022-05-16: MR<sup>3</sup> 22.5.2 Released.

[Change log](https://github.com/mr-3/MR3/commits/master)

# What is MR<sup>3</sup> ?
MR<sup>3</sup> (Meta-Model Management based on RDFs Revision Reflection) is an editing tool of RDF-based contents developed for managing a relationship between RDF and RDFS contents.

# Introduction
The Semantic Web is one of the most promised candidates as the Web tomorrow, whose basis is on [RDF](http://www.w3.org/TR/rdf-syntax-grammar/) and [RDF Schema](http://www.w3.org/TR/rdf-schema/) recommended by the World Wide Web Consortium. The purpose of the idea is to make the data on the Web available not only for displaying but also for automation, integration and reuse of data across various applications. At the moment, a number of supporting environment have been developed as the adopted tools of traditional knowledge engineering based ontologies. These products are mostly concentrating on creating ontologies and managing ontology-based semantic markup. From the standpoint of a significance of information lifecycle on the Semantic Web, in this work, an editing tool of RDF-based contents is developed for managing a relationship between RDF and RDFS contents.

# Features
MR<sup>3</sup> provides the three main functions to edit and to manage the several sorts of relationship among RDF and RDFS contents as follows.

## 1. Graphical Editing of RDF Descriptions
Based on the semantics of RDF data model, the tool supports to edit the resource-property-value relation.

## 2. Graphical Editing of RDFS Descriptions
Based on the semantics of RDF Schema model, the tool supports to edit the class-subclass relation and to add the information of properties such as range, domain, sub-property, and so on.

## 3. Meta-Model Management Facilities
In order to reflect the change of RDF or RDFS contents on the other, the tool supports the correspondence between them.

The above function consisted of the following sub-functions.

* Importing an RDF(S) document and editing the RDF(S) data model graphically.
* Exporting an RDF(S) data model as an RDF(S) document based on various formats such as Turtle, JSONLD, RDF/XML, and N-Triples.
* Reflecting changes of RDFS class to RDF resource type.
* Reflecting changes of RDFS property to RDF property.
* Reflecting the change of RDF resource type to the RDFS class and domains and ranges of RDFS property.
* Reflecting changes of RDF property to RDFS property.

# Paper
Takeshi Morita, Noriaki Izumi, Naoki Fukuta, Takahira Yamaguchi, “A Graphical RDF-based Meta-Model Management Tool”, IEICE Transactions on Information and Systems, Special Issue on Knowledge-Based Software Engineering Vol.E89-D No.4 pp.1368-1377, (2006), DOI: [10.1093/ietisy/e89-d.4.1368](http://doi.org/10.1093/ietisy/e89-d.4.1368)

```
@article{Morita2006,
  title={A Graphical RDF-based Meta-Model Management Tool},
  author={Takeshi MORITA and Naoki FUKUTA and Noriaki IZUMI and Takahira YAMAGUCHI},
  journal={IEICE Transactions on Information and Systems},
  volume={E89.D},
  number={4},
  pages={1368-1377},
  year={2006},
  doi={10.1093/ietisy/e89-d.4.1368}
}
```

# Contact
* Takeshi Morita (morita [at] it.aoyama.ac.jp)
