---
layout: default
permalink: /index
---

## What’s New
* 2016-04-14: MR<sup>3</sup> 1.0.1 Released.
* 2015-03-16: MR<sup>3</sup> 1.0 Released.
* 2005-12-29: MR<sup>3</sup> 1.0 RC5 Released.
* 2005-12-19: MR<sup>3</sup> 1.0 RC4 Released.
* 2005-12-04: MR<sup>3</sup> 1.0 RC3 Released.

[Change log](https://github.com/mr-3/MR3/commits/master)

## What is MR<sup>3</sup> ?
MR<sup>3</sup> (Meta-Model Management based on RDFs Revision Reflection) is an editing tool of RDF-based contents developed for managing a relationship between RDF and RDFS contents.

## Introduction
The Semantic Web is one of the most promised candidates as the Web tomorrow, whose basis is on [RDF](http://www.w3.org/TR/rdf-syntax-grammar/) and [RDF Schema](http://www.w3.org/TR/rdf-schema/) recommended by the World Wide Web Consortium. The purpose of the idea is to make the data on the Web available not only for displaying but also for automation, integration and reuse of data across various applications. At the moment, a number of supporting environment have been developed as the adopted tools of traditional knowledge engineering based ontologies. These products are mostly concentrating on creating ontologies and managing ontology-based semantic markup. From the standpoint of a significance of information lifecycle on the Semantic Web, in this work, an editing tool of RDF-based contents is developed for managing a relationship between RDF and RDFS contents.

## Features
MR<sup>3</sup> provides the three main functions to edit and to manage the several sorts of relationship among RDF and RDFS contents as follows.

#### 1. Graphical Editing of RDF Descriptions
Based on the semantics of RDF data model, the tool supports to edit the resource-property-value relation.

#### 2. Graphical Editing of RDFS Descriptions
Based on the semantics of RDF Schema model, the tool supports to edit the class-subclass relation and to add the information of properties such as range, domain, sub-property, and so on.

#### 3. Meta-Model Management Facilities
In order to reflect the change of RDF or RDFS contents on the other, the tool supports the correspondence between them.

The above function consisted of the following sub-functions.

* Transformation of RDF resources into graphical representation of RDF data model, including the management of different RDF resources and mapping the additional information to RDFS.
* Transformation of RDF data graph into RDF resource, including name-space management.
* Transformation of RDFS resources into graphical representation of RDF data model, including the management of different RDFS resources and visualize the side effects to the corresponding RDF resource.
* Transformation of RDFS data graph into RDFS resource, including name-space management.
* Reflecting the change of RDF resources on the corresponding RDFS resources, not only editing RDF resources but also loading new resources.
* Reflecting the change of RDFS resources on the corresponding RDF resources, as the same time above.


## Related Projects
* [DODDLE-OWL](http://doddle-owl.org/)


