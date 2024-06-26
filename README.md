
# Awesome Semantic Web [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of various semantic web and linked data resources.

To add something to the list please either submit a pull request or add a comment with a link to [issues/awesomelets](https://github.com/semantalytics/awesome-semantic-web/issues/81). Pull requests will be evaluated immediately for inclusion while awesomelets will be evaluated at some indeterminate time in the future.

Looking for something but can't find it? Add it to the ["Does it exist"](https://github.com/semantalytics/awesome-semantic-web/issues/74) list and we'll keep an eye out for it. If it's a good idea maybe someone will come along and create it!

## Contents

- [Standards](#standards)
- [Serialization](#serialization)
- [Datatypes](#datatypes)
- [Companies](#companies)
- [Industry](#industry)
- [Government](#government)
- [Research Institutions](#research-institutions)
- [Academic Journals](#academic-journals)
- [Databases](#databases)
- [SPARQL](#sparql)
  - [Streaming](#streaming-sparql)
  - [Federated](#federated-sparql)
  - [Applications](#sparql-applications)
  - [Benchmarks](#benchmarks)
- [GraphQL](#graphql)
- [Linked Data Fragments](#linked-data-fragments)
- [Linked Data Platform](#linked-data-platform-ldp)
- [Ecosystem](#ecosystem)
- [Knowledge Graph Management](#knowledge-graph-management)
- [Web Annotations](#web-annotations)
- [Mapping](#mapping)
- [Ontologies](#ontologies)
- [Ontology Development](#ontology-development)
- [Reasoners](#reasoners)
- [Books](#books)
- [Programming](#programming)
  - [C](#c)
  - [C\#](#c-1)
  - [Clojure](#clojure)
  - [Elixir](#elixir)
  - [Go](#go)
  - [Groovy](#groovy)
  - [Haskell](#haskell)
  - [Java](#java)
  - [JavaScript](#javascript)
  - [Kotlin](#kotlin)
  - [ObjectiveC](#objectivec)
  - [OCaml](#ocaml)
  - [Perl](#perl)
  - [PHP](#php)
  - [Prolog](#prolog)
  - [Python](#python)
  - [R](#r)
  - [Ruby](#ruby)
  - [Rust](#rust)
  - [Scala](#scala)
  - [Swift](#swift)
- [Editors](#editors)
- [Geo](#geo-1)
- [Visualization](#visualization)
- [Data Cube](#data-cube)
- [Datasets](#datasets)
- [IoT](#iot)
- [DevOps](#devops)
- [Platforms](#platforms)
- [Tools](#tools)
- [Integrations](#integrations)
- [Machine Learning](#machine-learning)
- [Linked Data](#linked-data)
- [CSVW](#csvw)
- [WebID](#webid)
- [SHACL Implementations](#shacl-implementations)
- [SKOS Tools](#skos-tools)
- [NLP](#nlp)
- [IIIF](#iiif)
- [Other Awesome](#other-awesome)
- [Misc](#misc)

## Standards

- [XSD Datatypes](https://www.w3.org/2011/rdf-wg/wiki/XSD_Datatypes)

### RDF

- [RDF 1.1 Primer](https://www.w3.org/TR/rdf11-primer/)
- [RDF 1.1 Semantics](https://www.w3.org/TR/rdf11-mt/)
- [RDF 1.1 Concepts and Abstract Syntax](https://www.w3.org/TR/rdf11-concepts/)
- [RDF 1.1: On Semantics of RDF Datasets](https://www.w3.org/TR/rdf11-datasets/)
- [RDF Dataset Canonocalization](https://json-ld.github.io/rdf-dataset-canonicalization/spec/) Unofficial Draft

### RDFS

- [RDF Schema 1.1](https://www.w3.org/TR/rdf-schema/)

### OWL

- [OWL 2 Web Ontology Language Document Overview](https://www.w3.org/TR/owl-overview/)
- [OWL 2 Web Ontology Language Primer](https://www.w3.org/TR/owl-primer/)
- [manchester](https://www.w3.org/2007/OWL/draft/ED-owl2-manchester-syntax-20081128/)
- [manchester-syntax-owl](https://github.com/rollxx/manchester-syntax-owl2)

### SHACL

- [SHACL Shapes Constraint Language](https://www.w3.org/TR/shacl/)
- [SHACL Advanced Features](https://www.w3.org/TR/shacl-af/)
- [SHACL JavaScript Extensions](https://www.w3.org/TR/shacl-js/)
- [SHACL Test Suite and Implementation Report](https://w3c.github.io/data-shapes/data-shapes-test-suite/#test-cases-format-and-process)


### ShEx

- [ShEx - Shape Expressions](http://shex.io)

### SPARQL

- [SPARQL 1.1 Overview](https://www.w3.org/TR/sparql11-overview/)
- [SPARQL 1.1 Query Language](https://www.w3.org/TR/sparql11-query/)
- [SPARQL 1.1 Update](https://www.w3.org/TR/sparql11-update/)
- [SPARQL 1.1 Service Description](https://www.w3.org/TR/sparql11-service-description/)
- [SPARQL 1.1 Federated Query](https://www.w3.org/TR/sparql11-federated-query/)
- [SPARQL 1.1 Query Results JSON Format](https://www.w3.org/TR/sparql11-results-json/)
- [SPARQL 1.1 Query Results CSV and TSV Formats](https://www.w3.org/TR/sparql11-results-csv-tsv/)
- [SPARQL 1.1 Query Results XML Format (Second Edition)](https://www.w3.org/TR/rdf-sparql-XMLres/)
- [SPARQL 1.1 Entailment Regimes](https://www.w3.org/TR/sparql11-entailment/)
- [SPARQL 1.1 Protocol](https://www.w3.org/TR/sparql11-protocol/)
- [SPARQL 1.1 Graph Store HTTP Protocol](https://www.w3.org/TR/sparql11-http-rdf-update/)

### R2RML

- [R2RML: RDB to RDF Mapping Language](https://www.w3.org/TR/r2rml/)

### RDFa

- [XHTML+RDFa 1.1 - Third Edition](https://www.w3.org/TR/xhtml-rdfa/)
- [RDFa Lite 1.1 - Second Edition](https://www.w3.org/TR/rdfa-lite/)
- [HTML+RDFa 1.1 - Second Edition](https://www.w3.org/TR/html-rdfa/)

### Tabular

- [CSV on the Web: A Primer](http://www.w3.org/TR/tabular-data-primer/)
- [Model for Tabular Data and Metadata on the Web](https://www.w3.org/TR/tabular-data-model/)
- [Metadata Vocabulary for Tabular Data](http://www.w3.org/TR/tabular-metadata/)
- [Generating JSON from Tabular Data on the Web](http://www.w3.org/TR/csv2json/)
- [Generating RDF from Tabular Data on the Web](http://www.w3.org/TR/csv2rdf/)
- [CSV on the Web: Use Cases and Requirements](http://www.w3.org/TR/csvw-ucr/)
- [Embedding Tabular Metadata in HTML](http://www.w3.org/TR/csvw-html/)

### Open Services for Lifecycle Collaboration (OSLC)

- [open-services.net](https://open-services.net/)

### Web Annotation Data Model

- [Web Annotation Data Model](https://www.w3.org/TR/annotation-model/)
- [Web Annotation Vocabulary](https://www.w3.org/TR/annotation-vocab/)
- [Web Annotation Protocol](https://www.w3.org/TR/annotation-protocol/)

### Linked Data Notifications

- [Linked Data Notifications](https://www.w3.org/TR/ldn/)

### Linked Data Platform

- [Linked Data Platform 1.0 Primer](https://www.w3.org/TR/ldp-primer/)
- [Linked Data Platform Best Practices and Guidelines](https://www.w3.org/TR/ldp-bp/)
- [Linked Data Platform 1.0](https://www.w3.org/TR/ldp/)
- [Linked Data Platform 1.0 Test Cases](https://dvcs.w3.org/hg/ldpwg/raw-file/tip/tests/ldp-testsuite.html)

### Linked Data Templates

- [Linked Data Templates](https://atomgraph.github.io/Linked-Data-Templates/)

### Linked Data Fragments (LDF)

- [Linked Data Fragments](http://linkeddatafragments.org)

### Data Cube extensions

- [QB4ST: RDF Data Cube extensions for spatio-temporal components](https://www.w3.org/TR/qb4st/)

## Serialization

| Format  | Description | Mime-type |
| :--- | :--- | :---: |
| [Turtle](https://www.w3.org/TR/turtle/) | Terse RDF Triple Language. | `text/turtle`, `application/x-turtle` |
| [TriG](https://www.w3.org/TR/trig/) | Plain text format for serializing named graphs and RDF Datasets. | `application/trig`, `application/x-trig` |
| [JSON-LD](https://json-ld.org/) | JSON-based Serialization for Linked Data. | `application/ld+json` |
| [RDF/JSON](https://www.w3.org/TR/rdf-json/) | RDF 1.1 JSON Alternate Serialization. | `application/rdf+json` |
| [N-Triples](https://www.w3.org/TR/n-triples/) | Line-based syntax for RDF datasets. |  `application/n-triples` |
| [N-Quads](https://www.w3.org/TR/n-quads/) | Line-based syntax for RDF datasets. | `application/n-quads`, `text/x-nquads`, `text/nquads` |
| [Notation3](https://www.w3.org/TeamSubmission/n3/) | Notation3 (N3): A readable RDF syntax. | `text/n3`, `text/rdf+n3` |
| [RDF/XML](https://www.w3.org/TR/REC-rdf-syntax/) | RDF/XML Syntax Specification. | `application/rdf+xml`, `application/xml` |
| [TriX](http://www.hpl.hp.com/techreports/2004/HPL-2004-56.html) | RDF Triples in XML. | `application/trix` |
| [HDT](https://www.w3.org/Submission/2011/03/) | Binary RDF Representation for Publication and Exchange. | `application/x-binary-rdf` |
| [aREF](https://gbv.github.io/aREF/aREF.html) | Another RDF Encoding Form. | |
| [RDF/POST](https://atomgraph.github.io/RDF-POST/) | RDF/POST Encoding for RDF. | `application/rdf+x-www-form-urlencoded` |
| [YARRML](http://rml.io/yarrrml/spec/) | YARRRML is a human readable text-based representation for declarative generation rules. It is a subset of [YAML], a widely used data serialization language designed to be  | | human-friendly. | |
| [hextuples](https://github.com/ontola/hextuples) | NDJSON serialization | |

## Datatypes

- [CDT](https://ci.mines-stetienne.fr/lindt/v2/custom_datatypes.html)
- [QUDT](http://www.qudt.org)
- [RDF Datatyping](http://infolab.stanford.edu/~melnik/rdf/datatyping/) - This document summarizes the common understanding of the RDF Core Working Group (further referred to as WG) with regards to the theoretical foundation for datatyping of literal values and serves as a basis of definition, discussion, and comparison of all proposed schemes for achieving a complete datatyping solution which are to be considered by the WG.

## Companies
Companies or businesses selling products with a primary focus on semantic web technology

- [Stardog Union](http://stardog.com) - Knowledge Graph Platform for the Enterprise.
- [Epimorphics](https://www.epimorphics.com/)
- [Franz](http://franz.com)
- [PoolParty](https://www.poolparty.biz/)
- [Cambridge Semantics](https://www.cambridgesemantics.com/)
- [Oxford Semantic Technologies](https://www.oxfordsemantic.tech/)
- [Capsenta](https://capsenta.com/)
- [Zazuko](https://zazuko.com/)
- [MarkLogic](https://www.marklogic.com/product/marklogic-database-overview/database-features/semantics/)
- [Oracle](https://www.oracle.com/technetwork/database/options/spatialandgraph/overview/rdfsemantic-graph-1902016.html)
- [OntoText](https://www.ontotext.com/)
- [TopQuadrant](https://www.topquadrant.com/)
- [OpenLinkSoftware](https://www.openlinksw.com/)
- [Cognitum](http://www.cognitum.eu/)
- [entryscape](https://entryscape.com)
- [inova8](http://www.inova8.com/)
- [in4mium](http://www.in4mium.com/)
- [Xylem Technologies](https://www.xylem-technologies.com/en/)
- [Synaptica](https://www.synaptica.com)
- [Ontola](http://ontola.io/)
- [eccenca Corporate Memory](https://www.eccenca.com) - build, explore and consume Knowledge Graphs
- [Semantic Arts](https://semanticarts.com) - Enterprise information systems based on flexible data structures and deep semantics.
- [Same4](http://www.seme4.com)
- [Derivo](https://www.derivo.de/en/home/)
- [Swirrl](https://www.swirrl.com/) - Linked-data publishing for Government organisations
- [SURROUND Australia](https://surroundaustralia.com) - Semantic Web consulting and enterprise semantics platform provision
- [AtomGraph](https://atomgraph.com/) - Free your data from silos
- [Ontopic](https://ontopic.ai/) - Create Knowledge Graphs from databases and datalakes. Core contributors to Ontop and experts in virtualization.
- [iNovex](https://mobi.inovexcorp.com/) - Web-based, collaborative ontology and vocabulary editor, and knowledge graph solution platform.

## Industry

Companies or businesses using semantic web technologies (alphabetical order):

- [BBC](https://www.bbc.com)
- [BestBuy](http://bestbuy.com)
- [DarkLight](https://www.darklight.ai) - DarkLight is an Artificial Intelligence Expert System for Active Cyber Defense and           Trusted Information Sharing.
- [DataLanguage](https://datalanguage.com/)
- [Eccenca](https://eccenca.com/en/)
- [Elsevier](https://www.elsevier.com) - Global information analytics business that helps institutions and professionals advance healthcare, open science and improve performance for the benefit of humanity
- [Field 33](https://field33.com) - Platform to build digital twins of organizations.
- [Facebook](http://facebook.com)
- [Google](http://google.com)
- [IBM](http://www.ibm.com)
- [K Health](https://khealth.ai) - Self diagnosing app.
- [NASA](https://www.nasa.gov)
- [Optum](https://www.optum.com) - Health related, known to use semantic graphs (marklogic).
- [Orange](https://www.orange.com) - International network infrastructure and service provider.
- [Osthus](https://www.osthus.com)
- [Perfect Memory](https://www.perfect-memory.com/) - DAM-as-a-Brain, a Platform that collects, interprets and makes any data and content actionable.
- [Schneider Electric](https://www.schneider-electric.com/ww/en/)
- [Siemens](https://www.siemens.com)
- [Volkswagen UK](https://www.volkswagen.co.uk)

## Government

- [Australian Government Linked Data Working Group](https://www.linked.data.gov.au) - Australian government's community of practice for Linked Data & Semantic Web
- [W3C's Gov enrment Linked Data Working Group archived wiki](https://www.w3.org/2011/gld/wiki/Main_Page) - "Developing standards which help governments publish their data as effective and usable Linked Data, using Semantic Web technologies"

## Research Institutions

- [AD Lab](https://ad.informatik.uni-freiburg.de/) - Freiburg, Germany
- [Agile Knowledge Engineering and Semantic Web (AKSW)](http://aksw.org) - The Research Group Agile Knowledge Engineering and Semantic Web (AKSW) is hosted by the Chair of Business Information Systems (BIS) of the Institute of Computer Science (IfI) / University of Leipzig as well as the Institute for Applied Informatics (InfAI).
- [Data Semantics Lab](https://daselab.cs.ksu.edu/) - Kansas State University, USA
- [Data Semantics Lab](https://dase.cs.wright.edu/) - Data Semantics Lab, Wright State University
- [DBIS Lab](http://dbis.informatik.uni-freiburg.de/) - Freiburg, Germany
- [DICE: Data Science Group](http://dice.cs.uni-paderborn.de/about/) - Universität Paderborn.
- [EURECOM](https://www.eurecom.fr/) - Ecole d'ingénieurs et centre de recherche en sciences du numérique, France. See its [Multimedia Semantics Group](https://semantics.eurecom.fr/wiki/Main_Page).
- [Exascale Infolab](https://exascale.info/projects/research/) - University of Fribourg, Switzerland
- [eXascale Infolab](https://exascale.info/) - eXascale Infolab, University of Fribourg, Switzerland.
- [IDLAB](https://www.ugent.be/ea/idlab/en/research/semantic-intelligence/semantic-knowledge-generation-and-publication-at-scale.htm) - Ghent University, Belgium
- [Knowledge Representation and Reasoning Group (KRR)](https://krr.cs.vu.nl/) - Research group is based at the Vrije Universiteit Amsterdam (VU).
- [Linköping University Semantic Web Group](https://www.ida.liu.se/research/semanticweb/) - Linköping University, Sweden
- [Max Planck Institute for Informatics](https://www.mpi-inf.mpg.de/departments/databases-and-information-systems/) - Department D5 of the Max Planck Institute for Informatics.
- [Ontology Engineering Group (OEG)](http://www.oeg-upm.net/) - The Ontology Engineering Group (OEG) is based at the Computer Science School at Universidad Politécnica de Madrid (UPM).
- [SWE @HTWK Leipzig](https://wse-research.org/) - Web & Software Engineering research group @ Leipzig University of Applied Sciences (HTWK Leipzig)
- [Stanford BMIR](https://bmir.stanford.edu) - Stanford University Center for Biomedical Informatics Research
- [The Smart Data Analytics (SDA)](http://sda.tech/) - Research group, Institute for Computer Science at the University of Bonn, the Fraunhofer Institute for Intelligent Analysis and Information Systems (IAIS) and the Institute for Applied Computer Science Leipzig.
- [University of Zurich Dynamic and Distributed Information Systems Group](http://www.ifi.uzh.ch/en/ddis.html)
- [WESO](http://www.weso.es/) - WESO is a research group at the University of Oviedo founded in 2004.
- [Wimmics](http://wimmics.inria.fr/corese) - Wimmics stands for Web-Instrumented Man-Machine Interactions, Communities, and Semantics, a joint research team between INRIA Sophia Antipolis - Méditerranée and I3S (CNRS and Université Côte d'Azur).

## Academic Journals

- [Semantic Web Journal](http://www.semantic-web-journal.net/)
- [Journal of Web Semantics](https://www.journals.elsevier.com/journal-of-web-semantics)
- [International Journal of Web and Semantic Technology](http://www.airccse.org/journal/ijwest/ijwest.html)
- [Applied Ontology](https://www.iospress.com/catalog/journals/applied-ontology)
- [Journal of Biomedical Semantics](https://jbiomedsem.biomedcentral.com/)

## Databases

$ - Proprietary
OS - OpenSource
F - Free

- [Vedas](https://github.com/Remixman/Vedas) - (OS) VEDAS is a RDF store engine that be able to query with SPARQL and run on single GPU.
- [Akutan](https://github.com/eBay/akutan) - (OS) A distributed knowledge graph store written in Golang. Formerly known as Beam.
- [Jena TDB](http://jena.apache.org/documentation/tdb/index.html) - (OS).
- [Ontotext GraphDB™](http://graphdb.ontotext.com/) - ($/F).
- [Halyard](https://github.com/Merck/Halyard) - (OS).
- [Stardog](http://stardog.com) - ($/F).
- [Strabon](http://www.strabon.di.uoa.gr/) - (OS) A spatiotemporal RDF store.
- [Systap Blazegraph™](https://www.blazegraph.com/) - ($/OS).
  - [docker-blazegraph](https://github.com/zorino/docker-blazegraph)
  - [blazegraph-samples](https://github.com/blazegraph/blazegraph-samples)
  - [docker-blazegraph](https://github.com/lyrasis/docker-blazegraph)
  - [blazegraph-service](https://github.com/vastix/blazegraph-service)
- [Marklogic](https://github.com/marklogic/semantic) - ($).
- [Virtuoso](https://virtuoso.openlinksw.com/) - ($/OS).
  - [virtuoso-opensource](https://github.com/openlink/virtuoso-opensource)
- [Oracle](http://www.oracle.com/technetwork/database/options/spatialandgraph/overview/rdfsemantic-more-2239071.html) - ($).
- [Allegrograph](http://franz.com/agraph/allegrograph/) - ($/F).
- [BrightstarDB](http://brightstardb.com/) - (OS) A native RDF database for the .NET platform written in C#.
- [CM-Well](https://github.com/thomsonreuters/CM-Well) - (OS).
- [Apache Rya](http://rya.incubator.apache.org/) - (OS).
- [4Store](https://github.com/garlik/4store) - (OS).
- [Mulgara](http://mulgara.org/) - (OS).
- [Parliament](https://github.com/SemWebCentral/parliament) - (OS).
- [SANSA](http://sansa-stack.net/) - (OS).
- [hbase-rdf](https://github.com/castagna/hbase-rdf) - (OS).
- [Anzograph](https://www.cambridgesemantics.com/product/anzograph/)
- [CumulusRDF](https://github.com/cumulusrdf/cumulusrdf)
- [Sempala](https://github.com/aschaetzle/Sempala)
- [TriplePlace](https://github.com/white-gecko/TriplePlace) - Light weight and flexible Triple Store for Android.
- [Node-Quadstore](https://beautifulinteractions.github.io/node-quadstore/) - (OS) A LevelDB-backed graph database for Node.js supporting quads, SPARQL queries and the RDF/JS interface.
- [KGRAM](http://wimmics.inria.fr/corese) - (OS).
- [luposdate](https://github.com/luposdate/luposdate) - (OS) Semantic Web database.
- [wallix/triplestore](https://github.com/wallix/triplestore) - (OS) Nifty library to manage, query and store RDF triples.
- [levelgraph](https://github.com/levelgraph/levelgraph) - (OS) Graph database JS style for Node.js and the Browser.
- [Oxford Semantic RDFox](https://www.oxfordsemantic.tech) - ($) Horizontly scalalbe in-memory triple store with parallel Datalog reasoning.
- [gStore](https://github.com/pkumod/gStore) - (OS) - a graph based RDF triple store.
- [ostrich](https://github.com/rdfostrich/ostrich) - (OS) bird Versioned RDF triple store (Offset-enabled TRIple store for CHangesets).
- [QuitStore](https://github.com/AKSW/QuitStore) - Quads in Git - Git versioned RDF Triple Store with support for branching and mergin and more.
- [NitrosBase](http://nitrosbase.com/) - (F)
- [Dydra](https://dydra.com) - ($) A cloud-based graph database.
- [redstore](https://github.com/njh/redstore) - (OS) RedStore is a lightweight RDF triplestore written in C using the Redland library.
- [librdf.sqlite](https://github.com/mro/librdf.sqlite) - (OS) improved SQLite RDF triple store for Redland librdf.
- [neptune](https://aws.amazon.com/neptune/) - ($) Amazon Neptune is a fast, reliable, fully managed graph database service that makes it easy to build and run applications that work with highly connected datasets.
- [fabric](https://github.com/spy16/fabric) - (OS) Fabric is a simple triplestore written in Golang.
- [kineo](https://github.com/kasei/kineo/) - (OS) A persistent RDF quadstore and SPARQL engine.
- [RDFox](http://www.oxfordsemantic.tech/) - ($)
- [Fluree](https://docs.flur.ee/) - (OS) Blockchain based triplestore.
- [Oxigraph](https://github.com/oxigraph/oxigraph) - (OS) a graph database implementing the SPARQL standard and written in Rust.
- [Triply](https://triply.cc) - (F/$)
- [Atomic-Server](https://crates.io/crates/atomic-server/) - (OS) Graph database + HTTP(S) server with authorization and versioning. Supports a strict subset of RDF.
- [RDF4j](https://rdf4j.org/) - (OS) Graph database supporting native, memory, LMDB, Solr, Elastic backends. Formerly known as Sesame.
- [Copernic](https://git.sr.ht/~amirouche/copernic) - (OS) Data, and its history, via change requests at scale.
- [Tentris](https://github.com/dice-group/tentris) - (OS) A tensor-optimized RDF data store, supporting SPARQL queries with Basic Graph Pattern capabilities.

### Academic
(Note: this classification is somewhat arbitrary and is meant to capture databases that only have a published paper or were developed for that purpose and are not actively maintained)

- [TripleRush](https://github.com/uzh/triplerush) - (OS).
- [corese](https://github.com/Wimmics/corese) - (OS).
- [rdf3x](https://code.google.com/archive/p/rdf3x/) - (OS).
- [gh-rdf3x](https://github.com/gh-rdf3x/gh-rdf3x) - (OS).
- [rdf3x-mpi](https://bitbucket.org/saikrishnan/rdf3x-mpi)
- [Qamel](https://github.com/dice-group/qamel) - RDF4J ported to Andriod.
- [dipLODocus](https://www.semanticscholar.org/paper/a1510214a16c73f464a8d1ae631054870114bbc8)
- [SW-Store](https://cs.uwaterloo.ca/~gweddell/cs848/papers/SW-Store.pdf)
- [Yars2](https://www.semanticscholar.org/paper/08bae32492f4f8a262ec990853613151cc484dc5)
- [Shard](https://sourceforge.net/projects/shard-3store/)
- [Hexastore](http://www.vldb.org/pvldb/1/1453965.pdf)
- [BitMat](https://www.cs.ox.ac.uk/people/medha.atre/papers/atre-ssws2009.pdf)
- [LUPOSDATE](https://www.ifis.uni-luebeck.de/index.php?id=luposdate-demo)
- [DREAM](https://github.com/CMU-Q/DREAM) - DREAM - Distributed RDF Engine with Adaptive Query Planner and Minimal Communication.
- [RIQ](https://github.com/UMKC-BigDataLab/RIQ) - RIQ is a new software tool for fast processing of SPARQL queries on RDF quadruples.
- [hyrise](https://github.com/hyrise/hyrise) - Hyrise is a research in-memory database.

## SPARQL

### Streaming SPARQL

- [CSPARQL-engine](https://github.com/streamreasoning/CSPARQL-engine)
- [Triplewave](https://github.com/streamreasoning/TripleWave)
- [morph-streams](https://github.com/jpcik/morph-streams)
- [Katts](https://github.com/uzh/katts) - Katts is A Triple Torrent Sieve.
- [WAVES](https://www.waves-rsp.org/)
- [Strider](https://github.com/renxiangnan/strider)
- [cqels](https://github.com/KMax/cqels)
- [morph](https://github.com/jpcik/morph) - Sparql-stream sensor queries.
- [morph-web](https://github.com/jpcik/morph-web)
- [sepa](https://github.com/arces-wot/SEPA) - A JAVA implementation of the SPARQL Event Processing Architecture including the engine, APIs and tools.
- [SMASSIF-RML](https://github.com/Orange-OpenSource/smassif-rml) - A Semantic Web stream processing solution with declarative data mapping capability based on a modified version of the RMLMapper-java tool and extensions to the StreamingMASSIF framework.
- [ssb-consum-up](https://github.com/Orange-OpenSource/ssb-consum-up) - A "Kafka to SPARQL gateway" standalone piece of software enabling end-to-end Semantic Web data flow architecture with a Semantic Service Bus (SSB) approach.
- [StreamingMASSIF](https://github.com/IBCNServices/StreamingMASSIF)
- [streaming-sparql](https://github.com/weblyzard/streaming-sparql)
- [Linked Data Event Streams](https://semiceu.github.io/LinkedDataEventStreams/) - The [Linked Data Event Stream (LDES) server](https://github.com/Informatievlaanderen/VSDS-LDESServer4J) is a configurable component that can be used to ingest, store, transform and (re-)publish an LDES 

### Federated SPARQL

ACTIVE

- [HeFQUIN](https://github.com/LiUSemWeb/HeFQUIN) - A query federation engine for heterogeneous federations of graph data sources.
- [Semagrow](https://github.com/semagrow)
- [CostFed](https://github.com/dice-group/CostFed)
- [QUETSAL](http://aksw.org/Projects/QUETSAL.html)
- [SPLENDID](http://ceur-ws.org/Vol-782/GoerlitzAndStaab_COLD2011.pdf)
- [ANAPSID](https://github.com/anapsid/anapsid)
- [HiBISCuS](https://github.com/AKSW/HiBISCuS)
- [SPARQLFederator](https://github.com/djogopatrao/SPARQLFederator)
- [rdffederator](https://github.com/goerlitz/rdffederator)
- [Avalanche](http://www.ifi.uzh.ch/en/ddis/research/avalanche.html)
- [FedX](https://github.com/VeritasOS/fedx)
- [anapsid](https://github.com/anapsid/anapsid) - An adaptive query processing engine for SPARQL endpoints.
- [luposdate](https://github.com/luposdate/luposdate) - A Semantic Web Database Management System developed by IFIS at the University of Lübeck.

ARCHIVE - inactive projects or old academic projects that may lack soruce code

- [SemWIQ](https://sourceforge.net/projects/semwiq/)
- [DARQ](http://darq.sourceforge.net/)

## Benchmarks

- [FedShop](https://github.com/GDD-Nantes/FedShop) - A Benchmark for Testing the Scalability of SPARQL Federation Engines
- [Berlin SPARQL Benchmark (BSBM)](http://wifo5-03.informatik.uni-mannheim.de/bizer/berlinsparqlbenchmark/)
- [Lehigh University Benchmark (LUBM)](http://swat.cse.lehigh.edu/projects/lubm/)
- [IGUANA](https://github.com/dice-group/IGUANA)
- [dice-group/triplestore-benchmarks](https://web.archive.org/web/20180627155808/https://github.com/dice-group/triplestore-benchmarks) - An Evaluation of Triplestore Benchamrks.
- [RdfStoreBenchmarking](https://www.w3.org/wiki/RdfStoreBenchmarking)
- [Hobbit](http://project-hobbit.eu/) - Holistic Benchmarking of Big Linked Data.
- [SP2Bench](http://dbis.informatik.uni-freiburg.de/index.php?project=SP2B)
- [IGUANA](https://github.com/AKSW/IGUANA) - IGUANA is a benchmark execution framework for triple stores.
- [SRBench](https://github.com/jpcik/srbench) - A streaming sparql benchmark.
- [TFT](https://github.com/BorderCloud/TFT) - TFT (Tester for Triplestore) is a script PHP to pass tests through a SPARQL service.
- [OTM Benchmark](https://kbss.felk.cvut.cz/web/kbss/otm-benchmark) - A benchmark of object-triple mapping (OTM) libraries.
- [LDBC](http://ldbcouncil.org/benchmarks)
- [GTFS-Madrid-Bench](https://github.com/oeg-upm/gtfs-bench) - A benchmark for performance and scalability of knowledge graph construction from heterogeneous data sources
- [GeoSPARQL Compliance Benchmark](https://github.com/OpenLinkSoftware/GeoSPARQLBenchmark) - A HOBBIT benchmark to check for the GeoSPARQL compliance of triple store implementations
- [RDF Library Benchmark](https://github.com/KonradHoeffner/rdf_benchmark) - Comparison of HDT and non-HDT RDF libraries for query time and memory usage.

### SPARQL Applications

- [SPARQL2Git](https://github.com/albertmeronyo/SPARQL2Git) - Easily store and curate SPARQL queries (and their associated Linked Data APIs) in GitHub.
- [sparql-transformer](https://github.com/D2KLab/sparql-transformer) - A generic JSON-LD transformer.
- [sparqlab](https://github.com/jindrichmynarz/sparqlab) - Lab for exercising SPARQL.
- [SNORQL](https://github.com/kurtjx/SNORQL) - Ajaxy front-end for exploring triple stores.
- [d3-sparql](https://github.com/zazuko/d3-sparql/) - Query a SPARQL endpoint with a SELECT query and get the data ready to be used with d3js
- [d3sparql](https://github.com/ktym/d3sparql) - JavaScript library for executing SPARQL query and transforming resulted JSON for visualization in D3.js.
- [jdbc4sparql](https://github.com/Claudenw/jdbc4sparql) - A JDBC driver that takes data from SPARQL endpoints or RDF graphs.
- [odata2sparql](https://github.com/peterjohnlawrence/com.inova8.odata2sparql.v4) - An OData proxy server that takes data from SPARQL endpoints or RDF graphs and publishes as OData V4 endpoint.
- [lens2odata](https://github.com/peterjohnlawrence/com.inova8.lens.framework.v4) - A GUI for discovery, search, and graph of RDF sources.
- [sparql2xquery](https://github.com/marklogic/sparql2xquery) - SPARQL to XQuery Translator for use with MarkLogic Semantic Toolkit.
- [SparqlAnalytics](https://github.com/AKSW/SparqlAnalytics)
- [decentsparql](https://github.com/itm/decentsparql)
- [sparqled](https://github.com/sindice/sparqled)
- [SPARQL2NL](https://github.com/AKSW/SPARQL2NL)
- [sparql-proxy](https://github.com/clarkparsia/sparql-proxy)
- [AutoSPARQL](https://github.com/AKSW/AutoSPARQL)
- [YASGUI](https://github.com/OpenTriply/YASGUI) - Yet Another Sparql GUI.
- [YASGUI.legacy](https://github.com/OpenTriply/YASGUI.legacy)
- [pubby](https://github.com/cygri/pubby) - A Linked Data frontend for SPARQL endpoints.
- [fluent-sparql](https://github.com/stoewer/fluent-sparql)
- [FlintSparqlEditor](https://github.com/TSO-Openup/FlintSparqlEditor)
- [reactive-sparql](https://github.com/modelfabric/reactive-sparql)
- [sparql-transformer](https://github.com/D2KLab/sparql-transformer)
- [spanqit](https://github.com/anqit/spanqit) - Java-based SPARQL query generator.
- [squebi](https://github.com/tkurz/squebi) - Squebi is a SPARQL editor and SPARQL result visualizer.
- [zeppelin-sparql](https://github.com/nick-manasys/zeppelin-sparql) - Zeppelin sparql interpreter.
- [SAFE](https://github.com/yasarkhangithub/SAFE)
- [Sparql-cli](https://github.com/lambdamusic/Sparql-cli) - Command line API for SPARQL.
- [snap-sparql-query](https://github.com/protegeproject/snap-sparql-query)
- [Trifid](https://github.com/zazuko/trifid) - Lightweight Linked Data Server and Proxy
- [asqc](https://github.com/gklyne/asqc) - SPARQL query client (pronounced "ask").
- [SPARQL-parser](https://github.com/tenforce/SPARQL-parser)
- [antlr-sparql-grammar](https://github.com/rollxx/antlr-sparql-grammar)
- [visu](https://github.com/jiemakel/visu) - Visual SPARQL query tool.
- [Porthole](https://itunes.apple.com/us/app/porthole/id984035787) - Mac SPARQL editor and client.
- [datastudio-sparql-connector](https://github.com/DataFabricRus/datastudio-sparql-connector) - SPARQL Connector for Google Data Studio.
- [QLever](https://github.com/ad-freiburg/QLever) - Highly efficient query engine for SPARQL+Text.
- [sage-engine](https://github.com/sage-org/sage-engine) - a SPARQL query engine for public Linked Data providers.
- [SEPA](https://github.com/arces-wot/SEPA) - A JAVA implementation of the SPARQL Event Processing Architecture including the engine, APIs and tools.
- [Processor](https://github.com/AtomGraph/Processor) - Ontology-driven Linked Data processor and server for SPARQL backends.
- [LinkedDataHub](https://atomgraph.github.io/LinkedDataHub/) - SPARQL-powered Knowledge Graph management system.
- [SparqlBlocks](http://sparqlblocks.org/) - Build SPARQL queries with blocks
- [SparqlProg](https://github.com/cmungall/sparqlprog) - composable SPARQL using logic programming
- [Sparklis](https://github.com/sebferre/sparklis) - natural language query builder to explore and query endpoints with all the power of SPARQL yet without any knowledge of SPARQL.
- [json-rql](https://json-rql.org/) - SPARQL with a JSON-LD super-set syntax (like GraphQL for the semantic web)

## GraphQL

- [semantic-graphql](https://github.com/nelson-ai/semantic-graphql) - Create GraphQL schemas from RDF ontologies.
- [hypergraphql](https://github.com/semantic-integration/hypergraphql) - GraphQL interface for querying and serving linked data on the Web.
- [UltraGraphQL](https://github.com/internet-of-production/UltraGraphQL) - extends HyperGraphQL with automatic bootstrapping phase and GraphQL mutations
- [Grasp](https://github.com/dbcls/grasp) - GraphQL endpoint wrapping SPARQL endpoints, declarative approach using [handlebars](https://handlebarsjs.com/guide/) Templates for SPARQL queries


## Linked Data Fragments

- [Linked Data Fragments](http://linkeddatafragments.org/)
- [tomayac/ldf-client](https://github.com/tomayac/ldf-client) - Polymer Linked Data Fragments client.
- [LDFlex](https://github.com/RubenVerborgh/LDflex) - A JavaScript DSL for querying Linked Data on the Web.
- [communica](http://comunica.linkeddatafragments.org/) - A modular framework for querying Linked Data on the Web.
- [HeFQUIN](https://github.com/LiUSemWeb/HeFQUIN) - A query federation engine for heterogeneous federations of graph data sources.

## Linked Data Platform (LDP)

- [fedora](https://duraspace.org/fedora/) - Repository platform with native linked data support.
- [warp](https://github.com/linkeddata/warp) - Warp an LDP file manager.
- [Marmotta](https://github.com/apache/marmotta) - Apache linked data platform implementation.
- [Elda](https://github.com/epimorphics/elda) - Linked data platform from Epimorphics.
- [LDP4j](https://github.com/ldp4j/ldp4j)
- [gold](https://github.com/linkeddata/gold) - Linked Data server for Go.
- [CarbonLDP](https://github.com/CarbonLDP) - ($)
- [trellis](https://github.com/trellis-ldp/trellis)
- [Metreeca/link](https://github.com/metreeca/link)
- [ldpserver](https://github.com/hectorcorrea/ldpserver) - A mini LDP Server written in Go.
- [ldp-coap-framework](https://github.com/sisinflab-swot/ldp-coap-framework) - Linked Data Platform for the Constrained Application Protocol
- [cavendish](https://github.com/cavendish-ldp/cavendish) - A LDP Implementation backed by BlazeGraph.

## Ecosystem

### Conferences

- [4th U.S. Semantic Technologies Symposium 2022](https://us2ts.org/)  
- [International Conference on Biomedical Ontology 2022](https://icbo-conference.github.io/icbo2022/)  
- [International Semantic Web Conference (ISWC 2019)](http://iswc2019.semanticweb.org)
- [European Semantic Web Conference (ESWC 2019)](https://2019.eswc-conferences.org)
- [US2TS -- U.S. Semantic Technologies Symposium](http://us2ts.org)
- [KGC - The Knowledge Graph Conference](https://www.knowledgegraph.tech)

### Blogs

- [Bob DuCharme's weblog technology for representing and linking information](http://www.snee.com/bobdc.blog/)
- [Planet RDF](http://planetrdf.com)
- [Jörn's Blog](https://joernhees.de/blog/)
- [Ontola Linked Data Blog](https://ontola.io/blog)
- [Semantic Arts Data-Centric Architecture blog](https://www.semanticarts.com/blog/)
- [TerminusDB Technical Blogs](https://github.com/terminusdb/technical-blogs)
- [Justin's Weblog](https://github.com/justin2004/weblog#readme)

### Groups

- [RDF-DEV](https://www.w3.org/community/rdf-dev/) - RDF-DEV COMMUNITY GROUP.
- [w3c semantic web](https://lists.w3.org/Archives/Public/semantic-web/)
- [JSON-LD Working Group](https://www.w3.org/2018/json-ld-wg/)
- [w3c activities](https://www.w3.org/Consortium/activities)
- [KG-Construction](https://www.w3.org/community/kg-construct/) - KG-Construction W3C Community Group

## Knowledge Graph Management

$ - Proprietary
OS - OpenSource

- [Metaphacts](http://metaphacts.com) - ($) End-to-end platform to create and utilize enterprise knowledge graphs.
- [OntoWiki](https://github.com/AKSW/OntoWiki) - (OS) Semantic data wiki as well as Linked Data publishing engine.
- [GNOSS-Sherlock](https://www.gnoss.com/en/semantic-framework/knowledge-graph-management) - ($) Cognitive Intelligence tool for machines to understand us.
- [Wikibase](http://wikiba.se) - (OS) Collection of applications and libraries for creating, managing and sharing structured data.
- [eccenca Corporate Memory](https://www.eccenca.com) - build, explore and consume Knowledge Graphs
- [Atomic Data Browser](https://github.com/joepio/atomic-data-browser) - (OS) Create, model, edit, view and share Linked Data.  
- [Blue Brain Nexus](https://bluebrainnexus.io/) - (OS) A knowledge graph for data-driven science 

## Web Annotations

- [anno4j](https://github.com/anno4j/anno4j)
- [annotation model](https://www.w3.org/TR/annotation-model/)

## Mapping

- [any2rdf](https://github.com/esbranson/any2rdf)
- [G2GML](https://g2gml.readthedocs.io/en/latest/contents/get-started.html) - Map RDF graphs to property graphs and output pg, json-pg, neo4j, pgx, aws or dot formats
- [triplify](https://github.com/pebbie/triplify)
- [pyrdb2rdf](https://github.com/nisavid/pyrdb2rdf)
- [xsparql](https://www.w3.org/Submission/xsparql-language-specification/)
- [triplify-csv](https://pypi.org/project/triplify-csv/) - CLI and Python package to generate triples or nquads from CSV files and a configuration file.
- [Karma](https://github.com/usc-isi-i2/Web-Karma) - Transform data expressed in multiple data formats into RDF.
- [Mapeathor](https://morph.oeg.fi.upm.es/tool/mapeathor) - Definition of Excel-based mappings and translation to [R2]RML mappings
- [RMLMapper](https://github.com/RMLio/rmlmapper-java) - Java-based RML Processor for transforming heterogeneous data into RDF.
- [RMLStreamer](https://github.com/RMLio/rmlmapper-java) - Flink-based RML Processor for transforming heterogeneous data into RDF in a streaming fashion.
- [RMLEditor](https://app.rml.io/rmleditor/) - Community Edition of the RML Editor to create RML mappings in a visual way.
- [ShExML](http://shexml.herminiogarcia.com/) - Shape Expressions Mapping Language. Map heterogeneous data via Shape Expression (ShEx).
- [ReDeFer XSD2OWL](https://rhizomik.net/redefer/xsd2owl) - Map XSD XML Schemas into the Web Ontology Language (OWL).
- [ReDeFer XML2RDF](https://rhizomik.net/redefer/xml2rdf) - Map XML into RDF.
- [Silk](http://silkframework.org/) - Linked data integration framework, connectes different linked data resources and transforms structured data source.

### Geo

- [geometry2rdf](https://github.com/boricles/geometry2rdf)
- [TripleGeo](https://github.com/GeoKnow/TripleGeo) - TripleGeo utility for converting geospatial data into triples.
- [GeoSPARQL](https://opengeospatial.github.io/ogc-geosparql/) - Major Open Geospatial Consortium Semantic Web spatial data stadard
- [GeoSPARQL DGGS](https://github.com/RDFLib/geosparql-dggs) - An RDFlib-based SPARQL extensions library for [Discrete Global Grid Systems](https://en.wikipedia.org/wiki/Discrete_global_grid) geospatial data

### Excel

- [TabLinker](https://github.com/Data2Semantics/TabLinker)
- [xlwrap](https://github.com/sidewinderlabs/xlwrap)
- [VocExcel](https://github.com/surroundaustralia/VocExcel) - A Excel -> SKOS RDF tool, based on RDFlib

### CSV/Tabular

- [guide-o-matic](https://github.com/baskaufs/guid-o-matic) - Xquery scripts to convert fielded text (CSV) files to RDF serialized as XML, Turtle, and JSON-LD.
- [COW](https://github.com/CLARIAH/COW) - CSV On the Web (CSVW) converter.
- [CSV2RDF](https://github.com/clarkparsia/csv2rdf) - CSV to RDF mapper.
- [csv2rdf](https://github.com/notruthless/csv2rdf)
- [csv2rdf4lod-automation](https://github.com/timrdf/csv2rdf4lod-automation)
- [tarql-component](https://github.com/opencube-toolkit/tarql-component)
- [tarql](https://github.com/tarql/tarql)
- [CSV2RDF](https://github.com/AtomGraph/CSV2RDF) - Streaming, transforming, SPARQL-based CSV to RDF converter
- [Morph-CSV](https://morph.oeg.fi.upm.es/tool/morph-csv) - Exploitation of RML+FnO and CSVW for ensuring the effectiveness of SPARQL-to-SQL systems.

### Object to RDF Mapping

- [java2rdf](https://github.com/EBIBioSamples/java2rdf) - A simple library to map Java objects and Java beans onto RDF/OWL
- [PA4RDF](https://github.com/Claudenw/PA4RDF) - functionality on top of an RDF store while accounting for and exploiting the fundamental differences between graph storage and relational storage.
- [Empire](https://github.com/mhgrove/Empire/) - JPA implementation for RDF
- [Pinto](https://github.com/stardog-union/pinto) - A lightweight framework for mapping Java Beans into RDF and back again
- [Som(m)er](https://github.com/bblfish/sommer) - Semantic Object (Metadata) MappER
- [jennabean](https://code.google.com/p/jenabean/)
- [Alibaba](https://bitbucket.org/openrdf/alibaba)
- [rdfbeans](https://github.com/cyberborean/rdfbeans)
- [surfrdf](https://github.com/cosminbasca/surfrdf) - SuRF: a python Object RDF Mapper (ORM).
- [jtriple](https://github.com/konradreiche/jtriple) - A Java object model binding for RDF.
- [sparql-template](https://github.com/gushakov/sparql-template) - RDF store traversal with Jena API via automatic mapping between POJO and SPARQL.
- [JOPA](https://github.com/kbss-cvut/jopa) - A Java object-triple mapping library for RDF4J, Jena and OWL API.
- [RomanticWeb](https://github.com/MakoLab/RomanticWeb) - RDF-Object Mapping for the Semantic Web.
- [XML2RDF-DataTransformation-MappingTool](https://github.com/isl/XML2RDF-DataTransformation-MappingTool) - XML2RDF Data Transformation Tool (Mapping Tool): This generic data transformation tool maps XML data files to RDF files, given a schema matching definition, based on this Mapping Language Schema.

### RDB to RDF

- [d2rq](https://github.com/d2rq/d2rq) - Database to RDF mapping engine and SPARQL server.
- [Sparqlify](https://github.com/AKSW/Sparqlify) - Sparql -> SQL Rewriter enabling virtual RDB -> RDF mappings.
- [Sparqlify-Extendsions](https://github.com/AKSW/Sparqlify-Extensions) - Extension projects for Sparqlify.
- [quetzal](https://github.com/Quetzal-RDF/quetzal) - SPARQL to SQL translation engine for multiple backends, such as DB2, PostgreSQL and Apache Spark.


### RDF to Property Graphs

- [sparql-gremlin](https://github.com/apache/tinkerpop/tree/master/sparql-gremlin) - SPARQL to Gremlin Translator available as a plugin of the popular Apache TinkerPop graph computing framework.
- [Gremlinator](https://github.com/LITMUS-Benchmark-Suite/sparql-to-gremlin/) - SPARQL to Gremlin standalone Translator available as an independent implementation for open use in custom use cases.


### XML

- [ontmalizer](https://github.com/srdc/ontmalizer) - Comprehensive transformations of XML Schemas (XSD) and XML data to RDF/OWL automatically.

#### R2RML

- [R2RML-Parser](https://github.com/nkons/r2rml-parser) - An R2RML implementation that can export relational database contents as RDF graphs.
- [Morph-KGC](https://github.com/oeg-upm/morph-kgc) - An R2RML engine that creates large knowledge graphs from RDB.
- [MusicBrainz-R2RML](https://github.com/LinkedBrainz/MusicBrainz-R2RML) - R2RML mappings for the MusicBrainz schema.
- [ontop](https://github.com/ontop/ontop) - Ontop is a platform to query relational databases as Virtual RDF Graphs using SPARQL. It's fast and is packed with features.
- [Ontopic Studio](https://ontopic.ai/en/ontopic-studio) - ($) Ontopic Studio is a GUI driven no-code application for designing standards compliant large R2RML mappings usable for Virtual RDF Graphs and RDF triple materialization. Academics can request free licenses.
- [db2triples](https://github.com/antidot/db2triples) - Antidot implementations of R2RML and Direct Mapping specifications.
- [R2RML-F](https://github.com/chrdebru/r2rml)
- [R2RML-api](https://github.com/R2RML-api/R2RML-api)
- [R2RML-kit](https://github.com/d2rq/r2rml-kit)
- [Juma](https://opengogs.adaptcentre.ie/crottija/juma-r2rml/) - Juma, jigsaw puzzles for representing mapping, is a method that applies the block metaphor to mapping languages.
- [pyrdb2rdf](https://github.com/nisavid/pyrdb2rdf) - A Python library for RDB2RDF Direct Mapping and R2RML.
- [sparqlmap](https://github.com/tomatophantastico/sparqlmap)
- [rdf2rml](https://github.com/VladimirAlexiev/rdf2rml) - R2RML Generation from simple examples.
- [ultrawrap](https://capsenta.com/) - ($)
- [AutoMap4OBDA](https://github.com/arc-lasalle/AutoMap4OBDA) - AutoMap4OBDA: Automated Generation of R2RML Mappings for OBDA.
- [Map-On](https://github.com/arc-lasalle/Map-On) - A web-based editor for visual ontology mapping for R2RML documents.
- [RMLMapper](https://github.com/RMLio/rmlmapper-java) - Java-based RML Processor backwards compatible with R2RML.

##### xR2RML

- [morph-xr2rml](https://github.com/frmichel/morph-xr2rml)
- [XR2RML](https://github.com/djimloic/XR2RML)

##### R2RML-F

- [paper](http://events.linkeddata.org/ldow2016/papers/LDOW2016_paper_14.pdf)
- [R2RML-F](https://github.com/chrdebru/r2rml)

#### RML

- [RML](https://github.com/RMLio) - RDF Mapping language for mapping JSON, CSV and XML to RDF.
- [CARML](https://github.com/carml/carml) - CARML RML engine for mapping CSV, XML and JSON files to RDF
- [RocketRML](https://github.com/semantifyit/RocketRML)
- [SDM-RDFizer](https://github.com/SDM-TIB/SDM-RDFizer) - RML engine for efficient transformation of CSV, RDB, XML and JSON to RDF
- [FuMap](https://github.com/SDM-TIB/FunMap) - Efficient preprocessing of transformation rules described in RML+FnO mappings.
- [Morph-KGC](https://github.com/oeg-upm/morph-kgc) - RML and RML-star engine that creates large knowledge graphs from heterogeneous data sources

#### Other RDF Mappings

- [sparql-generate](https://github.com/sparql-generate/sparql-generate)
- [SPARQL Anything](https://github.com/SPARQL-Anything/sparql.anything) - A system for Semantic Web [re-engineering](https://arxiv.org/pdf/2106.02361.pdf) that allows users to query anything with SPARQL.
- [any23](https://any23.apache.org/) - was "[moved into the Attic in 2023-06](https://attic.apache.org/projects/any23.html)"
- [J2RM](https://w3id.org/kgcp/J2RM/) - A tool to process mappings from JSON data to RDF triples guided by an OWL2 ontology structure.
- [mapping-template](https://github.com/cefriel/mapping-template) - A template-based component exploiting Apache Velocity to define mappings to/from RDF.

## Ontologies

- [LOV](https://lov.linkeddata.es) - Linked Open Vocabularies. Portal / search tool for vocabularies.
- [BioPortal](https://bioportal.bioontology.org) - Open repository with tools for ontologies and SKOS vocabularies; biomedical content dominates but all research domains welcome
- [prefix.zazuko.com](https://prefix.zazuko.com) - Similar to LOV, but with a richer search interface
- [Ontology Lookup Service (OLS)](https://www.ebi.ac.uk/ols/index) - OLS is a repository for biomedical ontologies that aims to provide a single point of access to the latest ontology versions.
- [OntoPortal](https://ontoportal.org) - The BioPortal software in Virtual Appliance (deployable) form
- [gist](https://www.semanticarts.com/gist/) - minimalist enterprise upper ontology - max coverage, fewest primitives, least ambiguity.
- [Plow](https://plow.pm) - Ontology package manager with semantic versioning and an [open domain-agnostic ontology registry that anyone can publish to](https://registry.field33.com).

### World Wide Web Consortium (W3C)

- [WGS84](https://www.w3.org/2003/01/geo/) - Basic Geo (WGS84 lat/long) Vocabulary.
- [skos](http://www.w3.org/2004/02/skos/core.html) - SKOS Simple Knowledge Organization System.
- [skos-xl](http://www.w3.org/TR/skos-reference/skos-xl.html) - SKOS Simple Knowledge Organization System eXtension for Labels.
- [vcard](https://www.w3.org/TR/vcard-rdf/) - vCard Ontology - for describing People and Organizations.
- [void](https://www.w3.org/TR/void/) - Describing Linked Datasets with the VoID Vocabulary.
- [time](https://w3c.github.io/sdw/time/) - Time Ontology in OWL.
- [org](https://www.w3.org/TR/vocab-org/) - The Organization Ontology.
- [data-cube](https://www.w3.org/TR/vocab-data-cube) - The RDF Data Cube Vocabulary.
- [pim](https://www.w3.org/2000/10/swap/pim/contact)
- [dqv](http://www.w3.org/ns/dqv#) - Vocabulary for describing quality metadata.
- [prov-o](https://www.w3.org/TR/prov-o/) - Represent provenance information.
- [dcat](https://www.w3.org/TR/vocab-dcat/) - DCAT is an RDF vocabulary designed to facilitate interoperability between data catalogs published on the Web.
- [prof](https://w3c.github.io/dxwg/profilesont/) The Profiles Ontology is an RDF vocabulary to describe profiles of (one or more) standards for information resources.

### European Commission
 - [Core Vocabularies](https://joinup.ec.europa.eu/collection/semantic-interoperability-community-semic/core-vocabularies) - Vocabularies developed for/by public administrations.

### Community

- [foaf](http://www.foaf-project.org/) - Friend of a Friend (FOAF) ontology.
- [uberon](http://uberon.github.io) - Integrated cross-species ontology covering anatomical structures in animals.
- [juso-ontology](http://rdfs.co/juso/latest/html) - Vocabulary for describing geographical addresses and features.
- [obo-relations](http://obofoundry.org/ontology/ro.html) - Relation Ontology. Relationship types shared across multiple ontologies.
- [orderedlistonto](https://github.com/smiy/orderedlistonto) - The Ordered List Ontology.
- [evidenceontology](http://evidenceontology.org) - EVIDENCE & CONCLUSION ONTOLOGY.
- [bevon](http://rdfs.co/bevon/latest/html) - Beverage ontology.
- [cyber-ontology](https://github.com/daedafusion/cyber-ontology) - Cyber Intelligence Ontology.
- [doap](https://github.com/edumbill/doap) - RDF schema for describing software projects.
- [qb4olap](https://github.com/lorenae/qb4olap) - A Vocabulary for Business Intelligence over Linked Data.
- [Hydra](https://github.com/lanthaler/Hydra) - A lightweight vocabulary for hypermedia-driven Web APIs.
- [vocab-transit](https://github.com/wwaites/vocab-transit) - RDF Schema for transit data.
- [ssso](https://github.com/gbv/ssso) - Specification of Simple Service Status Ontology.
- [dso](https://github.com/gbv/dso) - Specification of Document Service Ontology.
- [schema.org](https://schema.org/docs/datamodel.html) - Structured data on the Internet (Google, Microsoft, Yahoo and Yandex).
- [SPAR](http://www.sparontologies.net) - Semantic Publishing and Referencing Ontologies.
- [BFO](http://basic-formal-ontology.org) - Basic Formal Ontology.
- [CCO](https://github.com/CommonCoreOntology/) - Common Core Ontology Suite.
- [TOVE](http://www.eil.utoronto.ca/theory/enterprise-modelling/tove/) - Toronto Virtual Enterprise Ontologies. 
- [VIVO ISF](https://wiki.duraspace.org/display/VTDA/VIVO-ISF+Ontology) - Researchers and the full context in which they work.
- [yago](https://www.mpi-inf.mpg.de/departments/databases-and-information-systems/research/yago-naga/yago/) YAGO is a huge semantic knowledge base, derived from Wikipedia WordNet and GeoNames.
- [dbpedia](http://dbpedia.org/ontology/)

### Educational

- [MMOntologies](https://github.com/gatemezing/MMOntologies) - Multimedia ontologies studied for the paper "The Landscape of Multimedia Ontologies in the last Decade".
- [Wine](https://www.quora.com/What-is-wine-ontology) - Wine Ontology is a popular example of an OWL ontology.
- [Pizza](http://owl.cs.manchester.ac.uk/publications/talks-and-tutorials/protg-owl-tutorial/) - A step-by-step guide to modelling in OWL using the popular Protégé OWL tools.
  - [New Pizza](https://www.michaeldebellis.com/post/new-protege-pizza-tutorial) - An updated version of the well established pizza ontology tutorial covering Protégé 5+ as well as WebProtégé and introduces SHACL shapes.
- [W3C Best Practices for Publishing Linked Data](https://www.w3.org/TR/ld-bp/)
- [Coursera - Web of Data](https://www.coursera.org/learn/web-data/) - A joint initiative between EIT Digital, Université de Nice Sophia-Antipolis / Université Côte d'Azur and INRIA - introduces the Linked Data standards and principles that provide the foundation of the Semantic web.
- [Linked Data Patterns](http://patterns.dataincubator.org/book/index.html)
- [OBO Academy](https://oboacademy.github.io/obook/) - open, online, self-paced training materials on semantic engineering, ontology curation and ontology development.

## Ontology Development

- [protégé](http://protege.stanford.edu) - Ontology editor and framework for building intelligent systems.
- [OntoVerbal](https://github.com/TheOntologist/OntoVerbal) - OntoVerbal is a Protege 4.2 plugin that generates natural language descriptions for classes for an ontology written in OWL.
- [OTTR](https://ottr.xyz) - Reasonable Ontology Templates.
- [dosdp-tools](https://github.com/INCATools/dosdp-tools/) - dead simple owl design patterns (template tool)
- [OWLSharp](https://github.com/mdesalvo/OWLSharp) - .NET library for OWL2-DL ontology modeling, validation and reasoning
- [Ontology Development Kit](https://github.com/INCATools/ontology-development-kit/) - set up a git repo for developing an ontology
- [ROBOT](http://robot.obolibrary.org/) - command line swiss-army knife for ontology developers
- [grafo](http://gra.fo/) - Visual graph development
- [OOPS! (Ontology Pitfall Scanner!)](http://oops.linkeddata.es/) - a web application to detect (semi)automatically 33 pitfalls or errors in ontologies. A web service is also provided.
- [Cameo Concept Modeler](https://www.nomagic.com/product-addons/magicdraw-addons/cameo-concept-modeler-plugin#key-benefits) - a cross-platform app for OWL ontology modeling, visualization, and natural-language validation
- [Mobi](https://mobi.inovexcorp.com) - [Open Source](https://github.com/inovexcorp/mobi) (with an optional Enterprise version) system for developing ontologies and skos ocabularies with native graph versioning that enables a git-inspired workflow. More info [here](https://inovexcorp.github.io/mobi-docs/).

## Reasoners

- [Pellet](https://github.com/stardog-union/pellet)
- [openllet](https://github.com/Galigator/openllet)
- [FaCT++](https://github.com/ethz-asl/libfactplusplus) and [pyfactxx](https://github.com/tilde-lab/pyfactxx)
- [HermiT](http://www.hermit-reasoner.com/)
- [ELK](https://github.com/liveontologies/elk-reasoner)
- [Whelk](https://github.com/balhoff/whelk)
- [OWL-RL](https://github.com/RDFLib/OWL-RL)
- [RacerPro](https://franz.com/agraph/racer/)
- [Manchester List of Reasoners](http://owl.cs.manchester.ac.uk/tools/list-of-reasoners/)
- [elephant-reasoner](https://github.com/sertkaya/elephant-reasoner)
- [HyLAR](https://github.com/ucbl/HyLAR-Reasoner)
- [ruby-rdf/rdf-reasoner](https://github.com/ruby-rdf/rdf-reasoner)
- [cel](https://github.com/julianmendez/cel) -A lightweight Description Logic reasoner for large-scale biomedical ontologies.
- [reasonable](https://github.com/gtfierro/reasonable) - OWL 2 Reasoner built on DataFrog
- [eye](https://github.com/josd/eye) - Euler Yet another proof Engine.
- [Sequoia](https://github.com/andrewdbate/Sequoia) - Sequoia is a consequence-based OWL 2 DL Reasoner supporting multithreaded reasoning.
- [konclude](http://www.derivo.de/en/produkte/konclude.html) - Konclude is a high-performance reasoner for large and expressive ontologies.
- [owlproofs](https://github.com/klinovp/owlproofs) - Extension to the OWL API to request proofs of entailments from the reasoner.

## Books

- [Linked Data](https://www.manning.com/books/linked-data)
- [Explorer's Guide to the Semantic Web](https://www.manning.com/books/explorers-guide-to-the-semantic-web)
- [Semantic Web Programming](https://www.wiley.com/en-us/Semantic+Web+Programming-p-9781118080603)
- [Semantic Web for the Working Ontologist](http://workingontologist.org/)
- [Demystifying OWL for the Enterprise](https://www.morganclaypool.com/doi/10.2200/S00824ED1V01Y201801WBE017) [[1](https://link.springer.com/book/10.1007/978-3-031-79482-7)]
- [Programming the Semantic Web](http://shop.oreilly.com/product/9780596153823.do)
- [Building Ontologies with Basic Formal Ontology](https://direct.mit.edu/books/book/4044/Building-Ontologies-with-Basic-Formal-Ontology)
- [Structures for Organizing Knowledge: Exploring Taxonomies, Ontologies, and Other Schema](https://www.amazon.com/Structures-Organizing-Knowledge-Taxonomies-Ontologies/dp/1555706991)
- [Validating RDF Data](http://book.validatingrdf.com/)
- [Learning SPARQL](http://www.learningsparql.com/)
- [A Developer's Guide to the Semantic Web, 2014,2nd Ed](https://www.springer.com/us/book/9783662437957)
- [Ontology Engineering](https://www.morganclaypool.com/doi/abs/10.2200/S00834ED1V01Y201802WBE018)
- [The Data-Centric Revolution](https://www.amazon.co.uk/Data-Centric-Revolution-Restoring-Enterprise-Information/dp/1634625404)
- [An Introduction to Ontology Engineering, Keet, 2020, v1.5](https://people.cs.uct.ac.za/~mkeet/OEbook/) [[1](https://open.umn.edu/opentextbooks/textbooks/590)]

## Programming

### C

- [serd](https://github.com/drobilla/serd) - Lightweight C library for RDF syntax.
- [sord](https://github.com/drobilla/sord) - Sord is a lightweight C library for storing RDF statements in memory. 
- [librdf](https://github.com/dajobe/librdf) - Redland librdf RDF API and triple stores.
- [raptor](https://github.com/dajobe/raptor) - Redland Raptor RDF syntax library.
- [rasqal](https://github.com/dajobe/rasqal) - Redland Rasqal RDF Query Library.
- [cowl](https://github.com/sisinflab-swot/cowl) - A lightweight C API for working with OWL ontologies.

### C\#

- [dotNetRDF](https://github.com/dotnetrdf/dotnetrdf)
- [RDFSharp](https://github.com/mdesalvo/RDFSharp)
- [Rdf.Vocabularies](https://github.com/wikibus/rdf.vocabularies)

### C++

- [hdt-cpp](https://github.com/rdfhdt/hdt-cpp) - Read and query [HDT](https://www.rdfhdt.org/)

### Clojure

- [grafter](https://github.com/Swirrl/grafter) - Linked Data & RDF Manufacturing Tools in Clojure.
- [kr](https://github.com/drlivingston/kr) - Clojure API for RDF and SPARQL - provides consistent access to APIs including Jena and Sesame.
- [clj-plaza](https://github.com/antoniogarrote/clj-plaza) - Clojure rdf framework.
- [seabass](https://github.com/ryankohl/seabass) - A library for working with RDF with Jena in Clojure.
- [aristotle](https://github.com/arachne-framework/aristotle) - RDF, SPARQL and OWL for Clojure
- [aesopica](https://github.com/newres/aesopica) -  A Clojure library designed to help create Semantic Web based applications.
- [igraph](https://github.com/ont-app/igraph) -  IGraph defines a protocol which aims to provide a general interface to a variety of graph-based representations.
- [csv2rdf (clojure)](https://github.com/Swirrl/csv2rdf) - Clojure library and application for converting CSV to RDF
- [matcha](https://github.com/Swirrl/matcha) - :tea: SPARQL-like DSL for querying in-memory Linked Data Models
- [table2qb](https://github.com/swirrl/table2qb) - A generic pipeline for converting tabular data into rdf data cubes using csvw

### Elixir

- [RDF.ex](https://github.com/marcelotto/rdf-ex)

### Go

- [rdf2go](https://github.com/deiu/rdf2go) - Native golang library for RDF.
- [knakk/rdf](https://github.com/knakk/rdf) - RDF library for Go.

### Groovy

- [groovyrdf](https://github.com/angelo-v/groovyrdf)

### Haskell

- [rdf4h](https://github.com/robstewart57/rdf4h)
- [swish](https://hackage.haskell.org/package/swish)
- [hsparql](https://github.com/robstewart57/hsparql)

### Java

- [RDF4J](http://rdf4j.org)
- [Jena](http://jena.apache.org)
- [commons-rdf](http://commons.apache.org/proper/commons-rdf/)
- [foafssl-java](https://github.com/bblfish/foafssl-java)
- [soarql-dl-api](https://github.com/protegeproject/sparql-dl-api) - A query engine for SPARQL-DL.
- [nxparser](https://github.com/nxparser/nxparser) - Java parsers for different RDF serialisations + API + tools + JAX-RS integration.
- [Eclipse Lyo](https://www.eclipse.org/lyo/)
- [JB4JSON-LD](https://github.com/kbss-cvut/jb4jsonld), [JB4JSON-LD Jackson](https://github.com/kbss-cvut/jb4jsonld-jackson) - Java binding for JSON-LD (mapping POJO - JSON-LD).
- [titanium-json-ld](https://github.com/filip26/titanium-json-ld) - An implementation of the JSON-LD 1.1 (JSON-based Serialization for Linked Data) specification in Java utilizing Jakarta JSON Processing.
- [hdt-java](https://github.com/rdfhdt/hdt-java) - Read and query [HDT](https://www.rdfhdt.org/)

### JavaScript

- [js3](https://github.com/webr3/js3)
- [rdfstore-js](https://github.com/antoniogarrote/rdfstore-js)
- [sparql-engine](https://github.com/Callidon/sparql-engine) - An open-source framework for building SPARQL query engines in Javascript/Typescript.
- [rdf-ext](https://github.com/rdf-ext/rdf-ext)
- [N3.js](https://github.com/RubenVerborgh/N3.js)
- [Jessa](https://www.npmjs.com/package/jassa) - JAvascript Suite for Sparql Access.
- [RDFJS](https://github.com/rdfjs) - Github Organization that maintains modern JavaScript RDF libraries based on open, maintained standards
- [rdf.js](https://github.com/webr3/rdf.js)
- [rdflib.js](https://github.com/linkeddata/rdflib.js) - Linked Data API for JavaScript.
- [sparks](https://github.com/sparksrdf/sparks) - Sparks is a set of JavaScript libraries designed for simplifying the access to RDF data.
- [SPARQL.js](https://github.com/RubenVerborgh/SPARQL.js/) - A parser for the SPARQL query language in JavaScript.
- [sparqlalgebrajs](https://github.com/joachimvh/SPARQLAlgebra.js) - SPARQL to SPARQL Algebra converter.
- [RDForms](https://rdforms.org) - Construct form-based RDF editors in a web environment.
- [graphy.js](https://github.com/blake-regalia/graphy.js) - A collection of RDF libraries for JavaScript developers with a focus on performance and usability.
- [@zazuko/rdf-vocabularies](https://github.com/zazuko/rdf-vocabularies) - Library of common vocabularies
- [link-redux](https://github.com/fletcher91/link-redux/) - View RDF resources in React
- [@ontologies](https://github.com/ontola/ontologies) - Like @types, but for ontologies
- [rdfdev-js](https://github.com/ontola/rdfdev-js) - Collection of libraries to ease in JavaScript RDF development.
- [DataBorg/client](https://github.com/DataBorg/client) - Highly versatile SPARQL client for modern age

### Kotlin

- [kotlin-rdf](https://github.com/nicholashauschild/kotlin-rdf)

### ObjectiveC

- [SPARQLKit](https://github.com/kasei/SPARQLKit) - An implementation of the SPARQL 1.1 query language in Objective-C.

### OCaml

- [ocaml-rdf](https://www.good-eris.net/ocaml-rdf/) - Manipulate RDF graphs and execute Sparql queries.

### Perl

- [Attean](https://metacpan.org/pod/Attean)
- [RDF::Trine](https://metacpan.org/pod/RDF::Trine)

### PHP

- [EasyRdf](http://www.easyrdf.org/)
- [ARC2](https://github.com/semsol/arc2/wiki)
- [PHP-SPARQL-Lib](https://github.com/cgutteridge/PHP-SPARQL-Lib)
- [Graphite](http://graphite.ecs.soton.ac.uk/)
- [sparqllib](http://graphite.ecs.soton.ac.uk/sparqllib/)
- sweetrdf - Collection of RDF-libraries using modern PHP functionality
  - [rdfInterface](https://github.com/sweetrdf/rdfInterface) - Common interfaces for each RDF stack layer (parser, serializer, dataset, SPARQL client, etc.) to enable interoperability between different implementations. Think of it as PSR for RDF.
  - [quickRdf](https://github.com/sweetrdf/quickRdf) - A RDF library providing implementation of terms and dataset (using rdfInterface).
  - [quickRdfIo](https://github.com/sweetrdf/quickRdfIo) - Collection of RDF parsers and serializers (using rdfInterface)
  - [rdfHelpers](https://github.com/sweetrdf/rdfHelpers) - A set of helper classes for implementing the rdfInterface.
  - [sparqlClient](https://github.com/sweetrdf/sparqlClient) - A SPARQL client library for the rdfInterface ecosystem with the API inspired by the PDO.
  - and many more, see https://github.com/sweetrdf
 
### Prolog

- [SWI-Prolog Semantic Web Library](http://www.swi-prolog.org/pldoc/doc_for?object=section(%27packages/semweb.html%27))

### Python

- [RDFlib](https://github.com/RDFLib/rdflib) - A Python library for RDF manipulation, storage & serialization.
- [SPARQLWrapper](https://github.com/RDFLib/sparqlwrapper) - A wrapper for a remote SPARQL endpoint.
- [sparql-client](https://github.com/eea/sparql-client) - Python API to query a SPARQL endpoint.
- [RdfAlchemy](https://github.com/gjhiggins/RDFAlchemy)
- [Fuxi](http://code.google.com/p/fuxi/) - Bi-directional logical reasoning system for the semantic web.
- [PyShEx](https://github.com/hsolbrig/PyShEx) - ShEx interpreter for ShEx 2.0.
- [ORDF](http://ordf.org)
- [Django-rdf](http://code.google.com/p/django-rdf/) - An RDF engine for Django projects.
- [Djubby](https://github.com/wikier/djubby) - Linked Data frontend for SPARQL endpoints for Django.
- [SuRF](http://packages.python.org/SuRF/)
- [sparta](https://github.com/mnot/sparta/) - Simple API for RDF.
- [rdftools](https://github.com/cosminbasca/rdftools) - Simple collection of python RDF tools.
- [cysparql](https://github.com/cosminbasca/cysparql) - CySparql is a python wrapper over the excellent rasqal RDF library for parsing SPARQL queries.
- [pyHDT](https://github.com/Callidon/pyHDT) - Read and query [HDT documents](http://www.rdfhdt.org/) with ease in Python
- [calamus](https://github.com/SwissDataScienceCenter/calamus) - JSON-LD Serialization Library for Python based on Marshmallow
- [gastrodon](https://github.com/paulhoule/gastrodon) - Toolkit to display, analyze, and visualize data and documents based on RDF graphs and the SPARQL query language using Pandas, Jupyter, and other Python ecosystem tools.
- [kglab](https://github.com/DerwenAI/kglab/) -  The kglab library provides a simple abstraction layer in Python for building knowledge graphs.
- [AmpliGraph](https://github.com/Accenture/AmpliGraph) - Python library for Representation Learning on Knowledge Graphs.
- [Ontospy](https://github.com/lambdamusic/Ontospy) - Python library and command-line interface for inspecting and visualizing RDF models.
- [semantic-python-overview](https://github.com/pysemtec/semantic-python-overview) - List of Python specific semantic web tools and resources. 

### R

- [rrdf](https://github.com/egonw/rrdf)
- [rdflib](https://github.com/ropensci/rdflib)
- [redland](https://github.com/ropensci/redland-bindings)
- [jsonld](https://github.com/ropensci/jsonld)
- [csvwr](https://github.com/Robsteranium/csvwr) - Read and write CSVW tables and metadata in R
- [rcsvw](https://github.com/davideceolin/rcsvw) - R package that implements the candidate recommendations from the W3C CSV on the Web Working Group
- [Linked Data Frames](https://swirrl.github.io/linked-data-frames/) - Work with linked-data idiomatically in R using data frames (expresses RDF resources and descriptions as S3 objects)

### Ruby

- [ruby-rdf](http://ruby-rdf.github.io)
- [rdf-serializers](https://github.com/ontola/rdf-serializers) - Adds RDF serialization to Ruby on Rails active model serializers

### Rust

- [Horned OWL](https://github.com/phillord/horned-owl) - Horned-OWL is a library for manipulating OWL data.
- [Oxigraph](https://github.com/oxigraph/oxigraph) - Oxigraph is a graph database implementing the SPARQL standard.
- [sophia_rs](https://github.com/pchampin/sophia_rs) - Sophia: a Rust toolkit for RDF and Linked Data.
- [rio](https://github.com/oxigraph/rio) - Rio is a low level library which provides conformant and fast parsers and formatters for RDF related file formats.
- [rdf-rs](https://github.com/scholtzan/rdf-rs) - rdf is a library for the Resource Description Framework (RDF) and SPARQL implemented in Rust.
- [rome](https://github.com/vandenoever/rome) - Rome is an RDF library written in safe Rust.
- [atomic-lib](https://crates.io/crates/atomic-lib) - Library for managing and (de)serializaing Atomic Data, a strict subset of RDF.
- [harriet](https://github.com/field33/harriet) - A format-preserving serialization/deserialization library for Turtle.
- [owlish](https://github.com/field33/owlish) - An OWL library in Rust modeled on the OWL functional syntax.
- [RDFtk](https://github.com/johnstonskj/rust-rdftk) - An RDF Toolkit for Rust
- [hdt-rs](https://github.com/KonradHoeffner/hdt) - Read and query [HDT](https://www.rdfhdt.org/)

### Scala

- [banana-rdf](https://github.com/banana-rdf/banana-rdf) - A library for RDF, SPARQL and Linked Data technologies in Scala.
- [jvmrdftools](https://github.com/cosminbasca/jvmrdftools)
- [SANSA-RDF](https://github.com/SANSA-Stack/SANSA-RDF) - Library to read RDF files into Spark or Flink.
- [scowl](https://github.com/phenoscape/scowl) - A Scala DSL for programming with the OWL API.

### Swift

- [swift-sparql-syntax](https://github.com/kasei/swift-sparql-syntax) - SPARQL 1.1 Parser.
- [URITemplate](https://github.com/kasei/URITemplate) - Swift implementation of URI Template ([RFC6570](https://tools.ietf.org/html/rfc6570)).
- [swift-serd](https://github.com/kasei/swift-serd) - Swift package wrapper for the [Serd RDF library](http://drobilla.net/software/serd).
- [kineo](https://github.com/kasei/kineo) - A SPARQL endpoint and quadstore written in Swift.
- [swift-hdt](https://github.com/kasei/swift-hdt) - An [HDT](http://www.rdfhdt.org/) RDF Parser.

## Editors

### VIM

- [sparql.vim](https://github.com/vim-scripts/sparql.vim) - SPARQL syntax highlighting.
- [vim-sparql](https://github.com/Omer/vim-sparql)
- [semweb.vim](https://github.com/seebi/semweb.vim)

### Emacs

- [sparql-mode](https://github.com/ljos/sparql-mode)
- [ttl-mode](https://github.com/jeeger/ttl-mode) - Supports both ttl and n3, indentation, some electric punctuation and hungry delete.
- [nxml-mode](https://www.emacswiki.org/emacs/NxmlMode) - nxml-mode is a major mode for editing XML
- [ELOT](https://github.com/johanwk/elot) - Emacs Literate Ontology Tool, write OWL ontologies using org-mode

### JetBrains IDEs: Intellij IDEA, PyCharm, etc.

- [LNKD.tech Editor](https://plugins.jetbrains.com/plugin/12802-lnkd-tech-editor) - Editor for Turtle (Terse RDF Triple Language, TTL) files
- [RDF and SPARQL](https://rdfandsparql.com) - Adds support for the RDF 1.2 (Turtle, TriG, N-Triples, N-Quads), SPARQL 1.2 and ShExC 2.1 languages as well as a bunch of productivity features

### Visual Studio Code

- [Stardog RDF Grammars](https://marketplace.visualstudio.com/items?itemName=stardog-union.stardog-rdf-grammars)

### TextMate

- [sparql/turtle extension](https://github.com/peta/turtle.tmbundle)

### Sublime Text 3

- [Turtle and SPARQL syntax highlighter](https://github.com/abcoates/sublime-text-turtle-sparql)
- [Linked Data syntaxes](https://github.com/blake-regalia/linked-data.syntaxes) - Syntax highlighting for SPARQL 1.1/SPARQL*, Turtle/Turtle*, TriG, N-Triples, N-Quads, Notation3, and ShExC.

### BBedit

- [Turtle syntax highlighter](https://github.com/njh/bbedit-turtle)

## Geo

- [LinkedGeoData](https://github.com/GeoKnow/LinkedGeoData)
- [SemantGeo](https://github.com/apseyed/SemantGeo)
- [GeoLift](https://github.com/AKSW/GeoLift)
- [linkedspatialindex](https://github.com/wwaites/linkedspatialindex)
- [GeomRDF](https://github.com/fhamdi/GeomRDF)
- [GeoARQ](https://github.com/castagna/GeoARQ)
- [USeekM](https://www.openhub.net/p/useekm)

## Browsers

- [Galacteek](https://gitlab.com/galacteek/galacteek) - Multi-platform Qt5-based browser and semantic agent for the distributed web. Uses RDF graphs and P2P-SparQL to synchronize linked-data between peers.
- [LodView](https://github.com/LodLive/LodView) - RDF browser written in Java based on Spring and Jena using a SPARQL endpoint.
- [RhizomerEye](https://github.com/rhizomik/rhizomerEye) - A [Web application](https://rhizomik.net/rhizomer) for interactive exploration of semantic and linked data available from SPARQL endpoints.
- [RickView](https://github.com/konradhoeffner/rickview) - RDF browser for small knowledge bases written in Rust using an in-memory graph, doesn't require a SPARQL endpoint. Optimized for high performance and low resource usage.

## Visualization

- [Visual SPARQL Builder](https://leipert.github.io/vsb/)
- [d3-sparql](https://github.com/zazuko/d3-sparql)
- [SPARQLFilterFlow](http://sparql.visualdataweb.org/)
- [VOWL](http://vowl.visualdataweb.org/) - Visual Notation for OWL Ontologies.
- [gephi-semantic-web-import](https://github.com/Wimmics/gephi-semantic-web-import)
- [visualRDF](https://github.com/alangrafu/visualRDF)
- [rdfdot](https://github.com/wastl/rdfdot) - Tools for drawing graphs from RDF files with GraphViz.
- [ontodia](https://github.com/ontodia-org/ontodia) - Ontodia data diagraming library.
- [rdfpuml](https://github.com/VladimirAlexiev/rdf2rml) - True RDF Diagrams.
- [Ontology Visualisation](https://github.com/usc-isi-i2/ontology-visualization) - Create graphs from RDF using GraphViz.
- [SparqlBlocks](http://sparqlblocks.org/) - Build SPARQL queries with blocks
- [Cameo Concept Modeler](https://www.nomagic.com/product-addons/magicdraw-addons/cameo-concept-modeler-plugin#key-benefits) - a cross-platform app for OWL ontology modeling, visualization, and natural-language validation
- [Sparnatural](https://github.com/sparna-git/Sparnatural)
- [ReDeFer RDF2SVG](https://rdf2svg.redefer.rhizomik.net) - Render RDF as a SVG graph.
- [ReDeFer RDF2HTML](https://rhizomik.net/redefer/rdf2html) - Render RDF as HTML.
- [Zazuko's RDF Sketch](https://sketch.zazuko.com/) - Graphical RDF Explorer for small datasets
- [KinGVisher](https://wse-research.org/knowledge-graph-visualizer/) - Visualize knowledge graphs in a web browser

## Data Cube

- [QB4ST: RDF Data Cube extensions for spatio-temporal components](https://www.w3.org/TR/qb4st/)
- [The RDF Data Cube Vocabulary](https://www.w3.org/TR/vocab-data-cube/)
- [qb4olap-tools](https://github.com/lorenae/qb4olap-tools)
- [OpenCube-Expander](https://github.com/opencube-toolkit/OpenCube-Expander)
- [OpenCube Toolkit](http://opencube-toolkit.eu/)
- [CubeViz](https://github.com/AKSW/cubeviz.ontowiki)
- [NoSPA-RDF-Data-Cube-Validator](https://github.com/yyz1989/NoSPA-RDF-Data-Cube-Validator)
- [table2qb](https://github.com/swirrl/table2qb) - a pipeline for converting tabular data into rdf data cubes using csvw

## Datasets

- [BBC - Ontologies](https://www.bbc.co.uk/ontologies) - The ontologies the BBC is using to support its audience facing applications such as BBC Sport, BBC Education, BBC Music, News projects and more.
- [DBpedia](http://dbpedia.org)
- [geonames](https://github.com/ldodds/geonames)
- [permid](http://permid.org) - PermID: Connecting Data to the World.
- [wikidata](http://wikidata.org) - Wikidata is a free and open knowledge base that can be read and edited by both humans and machines.
- [lod-cloud](https://lod-cloud.net) - The Linked Open Data Cloud.

## IoT

- [Weviate](https://github.com/creativesoftwarefdn/weaviate)
- [rdfagents](https://github.com/joshsh/rdfagents) - Real-time messaging for the Semantic Web.

## DevOps

- [r43ples](https://github.com/plt-tud/r43ples) - Revision Management for the Semantic Web.
- [RDFUnit](https://github.com/AKSW/RDFUnit) - RDF Unit testing and validation framework.
- [rdf-toolkit](https://github.com/edmcouncil/rdf-toolkit) - RDF Serializer, to be used in a git commit-hook to force automatic correct rewrite of every OWL ontology.
- [TripleChecker](https://github.com/cgutteridge/TripleChecker) - Look for common errors in an RDF Document.
- [owl2vcs](https://github.com/utapyngo/owl2vcs) - owl2vcs is a set of tools designed to facilitate version control of OWL 2 ontologies using version control systems.
- [dowl](https://github.com/ldodds/dowl) - Generate docs for RDF/OWL Schema.
- [rdf-pipeline](https://github.com/rdf-pipeline)
- [rdfpatch](https://github.com/pchampin/ld-patch-py)
- [TurtleValidator](https://github.com/mmlab/TurtleValidator) - A Turtle validator on command line and in browser.
- [shi3ld-http](https://github.com/lukostaz/shi3ld-http) - Shi3ld for HTTP: Access control for HTTP operations on Linked Data.
- [babel](https://github.com/aidhog/blabel/) - A library for skolemising (or canonicalising) blank node labels in RDF graphs.
- [rdf.sh](https://github.com/seebi/rdf.sh) - A multi-tool shell script for doing Semantic Web jobs on the command line.
- [QuitStore](https://github.com/AKSW/QuitStore) - Quads in Git - Distributed Version Control for RDF Knowledge Bases.
- [QuitDiff](https://github.com/AKSW/QuitDiff) - Git diff into SparQL / Eccrev vocabulary.

## Platforms

- [trinity](https://bitbucket.org/semiodesk/trinity) - An application development platform for Microsoft .NET and Mono. It allows to easily build Linked Data and Semantic Web applications based on RDF.
- [Wings](https://github.com/IKCAP/wings) - A workflow system.
- [rww-play](https://github.com/read-write-web/rww-play) - An implementation in Play of a number of tools to build a Read-Write-Web server using Play2.x and akka.
- [prissma-studio](https://github.com/lukostaz/prissma-studio) - PRISSMA Studio: a web application to create Prisms, context-aware presentation metadata for Linked Data visualization.
- [lodspeakr](https://github.com/alangrafu/lodspeakr) - Framework to create Linked Data-based applications.
- [comunica](https://github.com/comunica/comunica) - Flexible meta query engine for the Web.
- [imagesnippets](http://www.imagesnippets.com/) - ImageSnippets is a complete metadata editing interface that enables someone who knows little to nothing about RDF, OWL, ontologies, or even URIs to create descriptions for images using Linked Data which is written in RDF.
- [Linked Data Reactor (LD-R)](http://ld-r.org) - A full-stack platform for building adaptive component-based Linked Data applications in NodeJS and React.
- [LDIF](https://github.com/wbsg/ldif) - Linked Data Integration Framework.
- [pyLDAPI](https://github.com/rdflib/pyLDAPI) - A Python [rdflib](https://github.com/rdflib/RDFlib/)-based API framework for Linked Data via the W3C's [Content Negotiation by Profile](https://w3c.github.io/dx-connegp/connegp/)
- [Chimera](https://github.com/cefriel/chimera) - A framework providing Apache Camel components to support data conversion to/from RDF and service integration with RDF graphs

## Tools

- [tawny-owl](https://github.com/phillord/tawny-owl) - Build OWL Ontologies in a Programmatic Environment.
- [Widoco](https://github.com/dgarijo/Widoco) - A Wizard for documenting and publishing ontologies on the Web.
- [sesame-vocab-builder](https://github.com/tkurz/sesame-vocab-builder) - Sesame Vocab Builder provides a command line tool that allows to create constants for RDF primitives for a given namespace out of RDF ontology files.
- [HydraConsole](https://github.com/lanthaler/HydraConsole)
- [qonsole](https://github.com/epimorphics/qonsole) - A simple console for running SPARQL queries and displaying results.
- [ntcat](https://github.com/cgutteridge/ntcat) - Command line tool for concatenating NTriples documents.
- [ripple](https://github.com/joshsh/ripple) - Semantic Web scripting language.
- [schema_salad](https://github.com/common-workflow-language/schema_salad) - Semantic Annotations for Linked Avro Data.
- [RDFConvert](https://sourceforge.net/projects/rdfconvert/) - RDFConvert is a simple command-line tool for converting RDF file betweeen different syntax formats.
- [ont-converter](https://github.com/sszuev/ont-converter) - Written in Kotlin, a simple command-line utility to convert any RDF graph to OWL2 ontology.
- [How to diff RDF](https://www.w3.org/2001/sw/wiki/How_to_diff_RDF)
- [Bubastis](https://github.com/EBISPOT/bubastis) - Tool for detecting asserted logical differences between two ontologies, such as between versions.
- [grlc](https://github.com/CLARIAH/grlc) - Web APIs from SPARQL queries.
- [Openlink Structured Data Sniffer](http://osds.openlinksw.com/) - Browser extension for Google Chrome, Microsoft Edge, Mozilla Firefox, Opera, and Vivaldi that unveils structured metadata embedded within HTML documents and web pages.
- [ShacShifter](https://github.com/AKSW/ShacShifter) - Shapes Constraint Language (SHACL) to various other format.
- [prefix.cc](https://prefix.cc) - namespace lookup for RDF developers
- [rdf2rdf](https://github.com/knakk/rdf2rdf) - Tool for converting between different RDF serialization formats.
- [Web-Client](https://github.com/AtomGraph/Web-Client) - Generic Linked Data browser and UX component framework.
- [CEDAR Workbench](https://metadatacenter.org) - Center for Expanded Data Annotation and Retrieval offers full life cycle management for semantically linked metadata
- [OnToology](https://github.com/OnToology/OnToology) - A system for collaborative ontology development. Given a GitHub repository with an OWL file, OnToology will survey it and produce diagrams, a complete documentation and validation based on common pitfalls.
- [OBA](https://github.com/KnowledgeCaptureAndDiscovery/OBA/) - Automatically create OpenAPI specifications from OWL and launch a server that serves JSON objects according to your ontology.
- [MEL](https://w3id.org/kgcp/MEL-TNNT/) - (*Metadata Extractor & Loader*) - A tool to extract metadata (and textual content) from various file formats, as JSON objects.
- [pyLODE](https://github.com/rdflib/pyLODE/) - A Python [rdflib](https://github.com/rdflib/RDFlib/)-based implementation of the [LODE](http://ceur-ws.org/Vol-932/paper12.pdf) ontology documentation tool
- [UnSHACLed](https://github.com/KNowledgeOnWebScale/unshacled) - A visual editor for RDF constraints currently supporting the visual notations ShapeUML and ShapeVOWL and import/export/validation of SHACL constraints.
- [rpt](https://github.com/SmartDataAnalytics/RdfProcessingToolkit) - Command line interface based RDF Processing Toolkit to run sequences of SPARQL statements ad-hoc on RDF datasets with a lot of features
- [RDF Playground](https://rdfplayground.dcc.uchile.cl/) - Browser based aggregation of multiple semantic web tools, includes syntax validation, visualization, reasoner and shacl validation

## Integrations

- [anthelion](https://github.com/yahoo/anthelion) - A plugin for Apache Nutch to crawl semantic annotations within HTML pages.
- [SolRDF](https://github.com/agazzarini/SolRDF) - An RDF plugin for Solr.
- [sesame-spring](https://github.com/ameingast/sesame-spring) - Spring integration for OpenRDF/Sesame.
- [HydraBundle](https://github.com/lanthaler/HydraBundle) - Symfony2 bundle which shows how easily Hydra can be integrated in modern Web frameworks.
- [SARQ](https://github.com/castagna/SARQ) - Free Text Indexing for SPARQL using a remote Solr server.
- [EARQ](https://github.com/castagna/EARQ) - EARQ is a combination of ARQ and ElasticSearch.
- [sesametools](https://github.com/joshsh/sesametools) - A collection of utilities for use with OpenRDF Sesame.
- [Imperium](https://github.com/mhgrove/Imperium) - Imperium is a plugin for the Play! framework similar to the existing JPA plugin that allows the use of Empire seamlessly in a Play! based application.
- [jekyll-rdf](https://github.com/white-gecko/jekyll-rdf) - A Jekyll plugin for including RDF data in your static site.
- [RightField](https://github.com/myGrid/RightField) - RightField is an open-source tool for adding ontology term selection to Excel spreadsheets.
- [mu-semtech](https://github.com/mu-semtech) - An Ecosystem of User-facing Microservices supported by Semantic Models.

## Machine Learning

- [LinkedPipes-ETL](https://github.com/linkedpipes/etl) - Linked Data ETL pipeline.
- [gm-sparql](https://github.com/ssrangan/gm-sparql) - Graph Mining Using SPARQL.
- [SANSA-Stack](http://sansa-stack.net) - Scalable Semantic Analytics Stack.
- [tdbloader4](https://github.com/castagna/tdbloader4) - Prototype to show how TDB indexes can be generated using MapReduce.
- [jena-grande](https://github.com/castagna/jena-grande) - Jena Grande is a collection of utilities, experiments and examples on how to use MapReduce, Pig, HBase or Giraph to process data in RDF format.
- [mrlin](https://github.com/mhausenblas/mrlin) - MapReduce processing of Linked Data.
- [infovore](https://github.com/paulhoule/infovore) - RDF-Centric Map/Reduce Framework and Freebase data conversion tool.
- [FOX](https://github.com/AKSW/FOX) - Federated Knowledge Extraction Framework.
- [signal-collect](https://github.com/uzh/signal-collect)
- [Duke](https://github.com/larsga/Duke) - Duke is a fast and flexible deduplication engine written in Java.
- [ODCS](https://github.com/mff-uk/ODCS) - The tool uses data processing pipelines for obtaining, processing, and storing RDF data.
- [etalis](https://github.com/sspider/etalis) - Event Processing SPARQL (EP-SPARQL).
- [graph-pattern-learner](https://github.com/RDFLib/graph-pattern-learner) - Evolutionary Graph Pattern Learner that learns SPARQL queries for a given set of source-target-pairs from an endpoint.
- [OntoGPT](https://github.com/monarch-initiative/ontogpt/) - Tools for populating semantic schemas from unstructured text using Large Language Models (LLMs)

## Linked Data

- [sieve](https://github.com/wbsg/sieve) - Linked Data Quality Assessment and Fusion.

## CSVW

- [Model for Tabular Data and Metadata on the Web](https://w3c.github.io/csvw/syntax/)
- [Metadata Vocabulary for Tabular Data](https://w3c.github.io/csvw/metadata/)
- [Generating RDF from Tabular Data on the Web (csv2rdf)](https://w3c.github.io/csvw/csv2rdf/)
- [RDF::Tabular](https://github.com/ruby-rdf/rdf-tabular) - Ruby gem to parse CSV or other Tabular Data into RDF and JSON
- [csvlint](https://github.com/Data-Liberation-Front/csvlint.rb) - Ruby gem to validate CSV files to check their syntax and contents
- [csv2rdf (clojure)](https://github.com/Swirrl/csv2rdf) - Clojure library and application for converting CSV to RDF
- [csv2rdf (ruby)](https://github.com/theodi/csv2rdf) - Ruby gem to convert CSV to RDF
- [csv2json](https://github.com/theodi/csv2json) - Ruby gem to convert CSV to JSON
- [COW](https://github.com/CLARIAH/COW) - Python package to convert CSV to RDF with nanopublications
- [csvw-parser](https://github.com/sebneu/csvw-parser) - Python package to parse CSVW
- [csvwr](https://github.com/Robsteranium/csvwr) - R package for reading and writing CSVW tables and metadata
- [rcsvw](https://github.com/davideceolin/rcsvw) - R package that implements the candidate recommendations from the W3C CSV on the Web Working Group
- [table2qb](https://github.com/swirrl/table2qb) - A generic pipeline for converting tabular data into rdf data cubes using csvw

## WebID

- [xwiki](https://github.com/bblfish/xwiki) - Xwiki related code for WebID.
- [solid-spec](https://github.com/solid/solid-spec)
- [webid-demo](https://github.com/digitalbazaar/webid-demo)
- [webid-spec](https://github.com/webid-community/webid-spec)
- [node-webid](https://github.com/magnetik/node-webid)

## SHACL Implementations

- [TopQuadrant/shacl](https://github.com/TopQuadrant/shacl) - SHACL API in Java based on Apache Jena.
- [RDFunit](https://github.com/AKSW/RDFUnit/)
- [labra/shaclex](https://github.com/labra/shaclex)
- [pySHACL](https://github.com/RDFLib/pySHACL) - A Python validator for SHACL.
- [rdf4j-shacl](http://docs.rdf4j.org/programming/#_validation_with_shacl)
- [shperone](https://forms.hypermedia.app) - Form Builder
- [Schímatos](https://github.com/schimatos/schimatos.org/) - A SHACL-based Web-Form Generator for Knowledge Graph Editing.
- [SHACL Playground](https://shacl-playground.zazuko.com/) - A web based SHACL validator
- [SHACLPlay](https://shacl-play.sparna.fr/play/)

## SKOS Tools

- [iQvoc](https://github.com/innoq/iqvoc) - SKOS(-XL) Vocabulary Management System for the Semantic Web.
- [Poolparty](https://www.poolparty.biz/skos-and-skos-xl) ($)
- [skosprovider](https://skosprovider.readthedocs.io/en/latest/intro.html) - Skosprovider provides an interface that can be included in an application to allow it to talk to different SKOS vocabularies.
- [skosshuttle](https://skosshuttle.ch/) ($)
- [atramhasis](https://github.com/OnroerendErfgoed/atramhasis)
- [ThManager](http://thmanager.sourceforge.net/)
- [protege skos editor](https://protegewiki.stanford.edu/wiki/SKOS_Editor)
- [skosmos](http://skosmos.org/)
- [Vocbench](http://vocbench.uniroma2.it/doc/user/skos_editing.jsf)
- [SKOS Play!](http://labs.sparna.fr/skos-play/about)
- [skosapi](http://skosapi.sourceforge.net/)
- [java-skos-api](https://github.com/simonjupp/java-skos-api)
- [askos](https://github.com/WileyLabs/askos) - A SKOS browser and editor.
- [VocPrez](https://github.com/RDFLib/VocPrez/) - A Linked Data API for SKOS data presentation

## NLP
- [fred](http://wit.istc.cnr.it/stlab-tools/fred/#About) - a machine reader for the Semantic Web
- [NIF](https://persistence.uni-leipzig.org/nlp2rdf/) NLP Interchange Format
- [Lemon](https://lemon-model.net/) - The Lexicon Model for Ontologies
- [Wordnet](https://wordnet.princeton.edu/)
- [PreMOn](http://premon.fbk.eu/ontology/vn) - Predicate Model for Ontologies (PreMOn) - VerbNet ontology module
- [BabelNet](https://babelnet.org)
- [TNNT](https://w3id.org/kgcp/MEL-TNNT/) - (*The NLP/NER Toolkit*) - A tool that automates the extraction of categorised named entities from the unstructured information encoded in the source documents, using diverse NLP tools and NER models.

## IIIF
- [IIIF](https://iiif.io/)
- [fester](https://github.com/UCLALibrary/fester)

## Other Awesome

- [awesome-graph](https://github.com/jbmusso/awesome-graph)
- [awesome-prolog](https://github.com/klaussinani/awesome-prolog)
- [awesome-ontologies](https://github.com/semantalytics/awesome-ontologies)
- [awesome-ontology](https://github.com/ozekik/awesome-ontology) - Similar to this list
- [shaoxiongi/awesome-knowlege-graph](https://github.com/shaoxiongji/awesome-knowledge-graph)
- [totogo/awesome-knowledge-graph](https://github.com/totogo/awesome-knowledge-graph)
- [awesome GLAM semweb](https://github.com/ncarboni/awesome-GLAM-semweb)
- [Awesome Knowledge Graph Construction Tools](https://github.com/kg-construct/awesome-kgc-tools)

## Misc

- [activitypub](https://www.w3.org/TR/2018/REC-activitypub-20180123/)
- [activitystrams-core](https://www.w3.org/TR/activitystreams-core/)
- [activitystreams](https://github.com/OpenSocial/activitystreams)
- [amazon-neptune-tools](https://github.com/awslabs/amazon-neptune-tools) - Tools and utilities to enable loading data and building graph applications with Amazon Neptune.
- [aurl](https://ctan.org/pkg/aurl) LaTeX package for hyperlinked URLs abbreviated with prefixes. The 1000 most common prefixes are predefined and more can be added.
- [awesome-semantic-web-business](https://github.com/KMax/awesome-semantic-web-business)
- [balloon](https://github.com/schlegel/balloon) - A tool-suite for Linked Data consumption. balloon aims in offering public services and tools to take advantage of the semantic web with less effort. The basic motivation is to establish a foundation for Linked Data as a Service (LDaaS).
- [basex-rdf](https://github.com/metadataframes/basex-rdf) - RDF parsing for BaseX.
- [basil](https://github.com/the-open-university/basil) - Building Apis SImpLy from sparql endpoints.
- [basil](https://github.com/the-open-university/basil) - Building Apis SImpLy from sparql endpoints.
- [Beast](https://github.com/SmartDataAnalytics/Beast) - Benchmarking, Evaluation, and Analysis Stack - A powerful yet lightweight Java8/Jena-based RDF processing stack.
- [canonical_rdf](https://github.com/iherman/canonical_rdf) - Proof-of-concept implementation of Aidan Hogan's RDF canonicalization algorithm in node.js.
- [carml-cli](https://github.com/netage/carml-cli) - Interface for CARML library.
- [cassa](https://github.com/heuer/cassa) - SPARQL 1.1 Graph Store HTTP Protocol implementation with plugable backends.
- [concurrent-rdf-graph](https://github.com/sszuev/concurrent-rdf-graph) - Concurrent RDF Graph implementations written in Kotlin.
- [CostFed](https://github.com/dice-group/CostFed) - Cost-Based Query Optimization for SPARQL Endpoint Federation.
- [cp-common-utils](https://github.com/mhgrove/cp-common-utils) - Collection of utilty classes from Clark & Parsia.
- [cp-openrdf-utils](https://github.com/mhgrove/cp-openrdf-utils) - Utility classes for working with the OpenRdf API.
- [CSO](https://cso.kmi.open.ac.uk/home) - The Computer Science Ontology (CSO) is a large-scale ontology of research areas that was automatically generated using the Klink-2 algorithm on the Rexplore dataset, which consists of about 16 million publications, mainly in the field of Computer Science.
- [csvw-template](https://github.com/edsu/csvw-template) - Document the semantics of your csv file.
- [datastudio-sparql-connector](https://github.com/DataFabricRus/datastudio-sparql-connector)
- [dbpedia-extension](https://github.com/sparkica/dbpedia-extension)
- [dcat-ap_validatyor](https://github.com/SEMICeu/dcat-ap_validator)
- [DEER](https://github.com/dice-group/DEER) - RDF Dataset Enrichment Framework.
- [dione](http://www.khaos.uma.es/dione) - Khoaos Research Group
- [docker2rdf](https://github.com/albertmeronyo/docker2rdf) - Mapper to represent Dockerfiles as RDF triples
- [eso-and-ceo](https://github.com/newsreader/eso-and-ceo) - Event and Implied Situation Ontology (ESO) and the Circumstantial Event Ontology for Calamities (CEO).
- [fbrs](https://github.com/aldonline/fbrs) - Facebook RDF Sync
- [fenster](https://github.com/knakk/fenster) - RDF quad-store frontend.
- [forgefed](https://github.com/forgefed/forgefed) - An extension to ActivityPub for web-based Git services federation.
- [fox-java](https://github.com/renespeck/fox-java) - Java bindings for FOX - Federated Knowledge Extraction Framework.
- [fox-py](https://github.com/earthquakesan/fox-py) - Python bindings for FOX - Federated Knowledge Extraction Framework.
- [fox-ui](https://github.com/Data2Semantics/fox-ui) - Web UI for FoxPSL.
- [fuxi](https://code.google.com/archive/p/fuxi/)
- [genealogical-trees](https://github.com/blokhin/genealogical-trees) - Semantic Web Exercise: Reasoning and Visualization of the Genealogical Ontologies.
- [Git2PROV](https://github.com/mmlab/Git2PROV) - Unleash the potential of Git in the new W3C standard for provenance.
- [GLEEN](https://github.com/RENCI-NRIG/gleen) Regular Paths for ARQ SparQL.
- [Glimmer](https://github.com/Timpy/Glimmer) - An RDF Search Engine.
- [Graphameleon](https://github.com/Orange-OpenSource/graphameleon) - A Web extension that captures Web navigation traces and transforms them into a RDF graph for further exploration.
- [grefine-rdf-extension](https://github.com/OpenRefine/grefine-rdf-extension) - An extension to Google Refine that enables graphical mapping of Google Refine project data to an RDF skeleton and then exporting it in RDF format.
- [grlc](https://github.com/CLARIAH/grlc) - Translates public SPARQL queries into Linked Data APIs automatically.
- [hydra-java](https://github.com/dschulten/hydra-java)
- [HydraClient](https://github.com/lanthaler/HydraClient)
- [IntervalServer](https://github.com/epimorphics/IntervalServer)
- [iRap](https://github.com/EIS-Bonn/iRap) - iRap - Interest-based RDF update propagation framework.
- [java-skos-api](https://github.com/simonjupp/java-skos-api) - The SKOS API provides a Java interface and OWL API based implementation of the Simple Knowledge Organisation System (SKOS)
- [jdbc-for-rdf3x](https://github.com/dbiir/jdbc-for-rdf3x)
- [jena-joseki](https://github.com/tingletech/jena-joseki)
- [jena-sparql-api](https://github.com/SmartDataAnalytics/jena-sparql-api) - A collection of Jena-extensions for hiding SPARQL-complexity from the application layer.
- [JenaSecurity](https://github.com/Claudenw/JenaSecurity) - Security (Permissions) wrapper around Jena RDF implementation.
- [jqudt](https://github.com/egonw/jqudt) - Java library for working with the QUDT ontology and data using it.
- [json-ld-macros](https://github.com/antoniogarrote/json-ld-macros)  Declarative transformation of JSON APIs into JSON-LD.
- [jsonld-java](https://github.com/jsonld-java/jsonld-java) - JSON-LD implementation for Java.
- [jsonld-streaming-parser.js](https://github.com/rubensworks/jsonld-streaming-parser.js) - A fast and lightweight streaming JSON-LD parser for JavaScript.
- [kbpedia](https://github.com/Cognonto/kbpedia) - KBPedia Knowledge Graph & Knowledge Ontology (KKO).
- [keygenapp](https://github.com/bblfish/keygenapp) - Utilities and WebApp for certificate creation within a browser, for FOAF+SSL.
- [knowledgecubes](https://github.com/amgadmadkour/knowledgecubes) - Efficient RDF Data Management over Spark.
- [LD-FusionTool](https://github.com/mifeet/LD-FusionTool) - Data Fusion & Conflict Resolution tool for Linked Data.
- [LD-FusionTool](https://github.com/mifeet/LD-FusionTool) - Data Fusion & Conflict Resolution tool for Linked Data.
- [ldpatch](https://www.w3.org/TR/ldpatch/)
- [levelgraph-jsonld](https://github.com/mcollina/levelgraph-jsonld) - The Object Document Mapper for LevelGraph based on JSON-LD
- [levelgraph-n3](https://github.com/levelgraph/levelgraph-n3) - LevelGraph plugin for storing N3/Turtle/RDF data.
- [linked-csv-browser](https://github.com/theodi/linked-csv-browser)
- [linked-csv](https://github.com/JeniT/linked-csv) - A souped-up CSV-based data format.
- [Linked-Data-Studio](https://github.com/architolk/Linked-Data-Studio) - The Linked Data Studio is an extension to the Linked Data Theatre for the creation of Linked Data.
- [Linked-Data-Theatre](https://github.com/architolk/Linked-Data-Theatre) - The Linked Data Theatre is a platform for an optimal presentation of Linked Data.
- [linkeddatafragments](http://comunica.linkeddatafragments.org/)
- [LODGrefine](https://github.com/sparkica/LODGrefine) - LOD-enabled Google Refine: linked open data related extensions included.
- [LodLive](https://github.com/dvcama/LodLive) - browse the web of data - a SPARQL navigator http://lodlive.it
- [lodmill](https://github.com/lobid/lodmill) - Blend, grind, and enjoy LOD – fresh from the mill!
- [LSD-Dimensions](https://github.com/albertmeronyo/LSD-Dimensions) - All dimension values of Linked Statistical Data.
- [Luzzu](https://github.com/Luzzu/Framework/) - A scalable and extensible Linked Data quality assessment framework.
- [m-ld](https://m-ld.org/) - Real-time information sharing component using RDF and conflict-free replicated data types (CRDTs)
- [Mandolin](https://github.com/mommi84/Mandolin) - sparkle Markov Logic Networks for the Discovery of Links
- [mediation](https://github.com/correndo/mediation) - Jena based framework to implement ontological mediation of SPARQL queries.
- [metrecca/link](https://github.com/metreeca/link) - Metreeca Model-Driven Linked Data Framework .
- [metreeca](https://github.com/metreeca) - The model-driven linked data platform.
- [ML-Schema/core](https://github.com/ML-Schema/core) - CORE ontology of ML-Schema schema. It's the mapping to others machine learning vocabularies and ontologies (DMOP, Expose, OntoDM and MEX)
- [MOD-Ontology](https://github.com/sifrproject/MOD-Ontology) - Metadata for Ontology Description and Publication Ontology .
- [module-extractor](https://github.com/rsgoncalves/module-extractor) - Java-based module extractor for OWL ontologies.
- [morph-starter](https://github.com/jpcik/morph-starter) - this project is a simple Java (and Scala) demo of how to use morph.
- [motools](https://github.com/motools) - Music ontology tools
- [n3pygments](https://github.com/gniezen/n3pygments) - Pygments lexer to perform syntax highlighting for N3, Turtle and SPARQL.
- [nanopub-java](https://github.com/Nanopublication/nanopub-java)
- [nichtich/wdg](https://github.com/nichtich/wdq) - Command line interface to Wikidata Query Service.
- [NSpM](https://github.com/AKSW/NSpM) - robot Neural SPARQL Machines translate natural language into SPARQL queries.
- [odmtp-tpf](https://github.com/benjimor/odmtp-tpf) - Triple pattern matching over non-RDF datasources with inference .
- [OLGA](https://ecostruxure.github.io/OLGA/) - OLGA (Ontology Library GenerAtor) is a generic tool aiming to accelerate the adoption of Standard W3C Semantic technology among developers.
- [OME](https://github.com/oeg-upm/OME) - Online Mapping Editor.
- [omv2](http://omv2.sourceforge.net/)
- [ONT-API](https://github.com/owlcs/ont-api) - a Jena based OWL-API implementation (Java library).
- [ontmalizer](https://github.com/srdc/ontmalizer) - A tool that performs comprehensive transformations of XML Schemas (XSD) and XML data to RDF/OWL automatically
- [ontodia](https://github.com/sputniq-space/ontodia) - Ontodia data diagraming library.
- [opensemanticsearch](https://github.com/opensemanticsearch)
- [openskos](http://openskos.org/)
- [ORE](https://github.com/AKSW/ORE) - Ontology Repair and Enrichment.
- [ostrich](https://github.com/rdfostrich/ostrich) -Versioned RDF triple store (Offset-enabled TRIple store for CHangesets)
- [OWL-API](https://github.com/owlcs/owlapi) - The OWL API is a Java API for creating, manipulating and serialising OWL Ontologies.
- [owl-functional-syntax-axiom-parser](https://github.com/dfleischhacker/owl-functional-syntax-axiom-parser)
- [owlapitools](https://github.com/owlcs/owlapitools) - Set of independent add-ons for OWL API.
- [owlconvert](https://github.com/camwebb/owlconvert) - Simple OWL format converter based on OWLAPI.
- [pikes](http://pikes.fbk.eu) - Pikes is a Knowledge Extraction Suite
- [platform-linked-data-nederland](http://www.pilod.nl/wiki/Platform_Linked_Data_Nederland)
- [prefix.cc](https://github.com/cygri/prefix.cc) - Source code to the prefix.cc website.
- [premon](https://premon.fbk.eu) - PREdicate Model for ONtologies
- [prissma](https://github.com/lukostaz/prissma) - Context-Aware Adaptation for Linked Data.
- [profilechecker](https://github.com/stain/profilechecker) - OWL API profile checker.
- [psparql](http://exmo.inrialpes.fr/software/psparql/) - PSPARQL (for Path SPARQL) is a query language for RDF.
- [psps](https://github.com/factsmission/psps) - Personal Structured Publishing Space.
- [psps](https://github.com/factsmission/psps) - Personal Structured Publishing Space.
- [rabel](https://github.com/linkeddata/rabel) - Program for reading and writing linked data in various formats.
- [rdf-delta](https://afs.github.io/rdf-delta/)
- [rdf-patch](https://afs.github.io/rdf-patch/)
- [rdf-protege](https://github.com/sszuev/rdf-protege) - a Protege Desktop fork with RDF support.
- [rdf-thrift](https://afs.github.io/rdf-thrift/)
- [rdf.sh](https://github.com/seebi/rdf.sh) - A multi-tool shell script for doing Semantic Web jobs on the command line.
- [rdf2h](https://github.com/rdf2h/rdf2h) - Render resources described in RDF using logicless templates.
- [rdf3x_path](https://github.com/agubichev/rdf3x_path) - RDF3X with path queries.
- [rdf4a](https://github.com/MM2-0/rdf4a) - RDF4J for Android.
- [rdfpro](https://github.com/dkmfbk/rdfpro) - a public domain, Java command line tool and library for RDF processing.
- [rdfpro](https://github.com/dkmfbk/rdfpro) - an extensible tool for building stream-oriented RDF processing pipelines.
- [rdfshape](http://rdfshape.herokuapp.com/)
- [rdfsurveyor](https://github.com/guiveg/rdfsurveyor) - Exploration tool for RDF datasets.
- [redland-bindings](https://github.com/dajobe/redland-bindings) - Redland librdf language bindings.
- [rif4j](http://rif4j.sourceforge.net/)
- [robot](http://robot.obolibrary.org/) - ROBOT is a command line tool for working with Open Biomedical Ontologies
- [rocker](https://github.com/AKSW/rocker) - key A Refinement Operator Approach for Key Discovery. http://aksw.org/projects/Rocker
- [rollxx/antlr-sparql-grammar](https://github.com/rollxx/antlr-sparql-grammar) - sparql 1.1 antlr grammar.
- [rollxx/manchester-syntax-owl2](https://github.com/rollxx/manchester-syntax-owl2) - ANTLR grammar for simplified Manchester Syntax OWL2.
- [Rule-Translator](https://github.com/ismailakbari/Rule-Translator) - This is framework is a Web rule translator. It has a rule parser, visualizer and translator. The Web rule languages that are covered by this framework include: Notation3 (N3), POSL, Datalog RuleML, SWRL and RIF. This framework is a rule engine for RIF language as well.
- [scylla-rdf](https://github.com/DataFabricRus/scylla-rdf
- [SemanticPingback](https://github.com/AKSW/SemanticPingback) - This small vocabulary defines resources which are used in the context of Semantic Pingback.
- [semargl](https://github.com/semarglproject/semargl) - Highly performant, lightweight framework for linked data processing. Supports RDFa, JSON-LD, RDF/XML and plain text formats, runs on Android and GAE, provides integration with Jena, Sesame and Clerezza.
- [semwiki](https://github.com/pchampin/semwiki) - An experimental semantic wiki with bidirectional (text <-> triples) changes.
- [SEPA](https://github.com/arces-wot/SEPA) - A JAVA implementation of the SPARQL Event Processing Architecture including the engine, APIs and tools.
- [SEPA](https://github.com/arces-wot/SEPA) - A JAVA implementation of the SPARQL Event Processing Architecture including the engine, APIs and tools.
- [SEPA](https://github.com/arces-wot/SEPA/blob/master/README.md)
- [sesametools](https://github.com/joshsh/sesametools) - A collection of utilities for use with OpenRDF Sesame (as of recently, Eclipse RDF4J).
- [signal-collect-torque](https://github.com/uzh/signal-collect-torque) - Support for Signal/Collect Torque deployment.
- [silk](http://silk.semwebcentral.org/) - Semantic Inferencing on Large Knowledge (SILK) knowledge representation system.
- [solr-ontology-tagger](https://github.com/opensemanticsearch/solr-ontology-tagger) - Automatic tagging and analysis of documents in an Apache Solr index for faceted search by RDF(S) Ontologies & SKOS thesauri.
- [sparql-ld](https://github.com/fafalios/sparql-ld) - SPARQL-LD: A SPARQL Extension for Fetching and Querying Linked Data.
- [sparql-ld](https://github.com/fafalios/sparql-ld) - SPARQL-LD: A SPARQL Extension for Fetching and Querying Linked Data.
- [sparql-ld](https://github.com/fafalios/sparql-ld) - SPARQL-LD: A SPARQL Extension for Fetching and Querying Linked Data.
- [sparql-to-csv](https://github.com/jindrichmynarz/sparql-to-csv) - Stream SPARQL results to CSV .
- [sparti](https://github.com/amgadmadkour/sparti) - SPARTI - RDF Semantic Partitioning.
- [spdx](https://spdx.org/specifications) - Software Package Data Exchange® (SPDX®) is an open standard for communicating software bill of material information (including components, licenses, copyrights, and security references).
- [specgen](https://github.com/specgen/specgen) - Modified, extended and more generalized version of Danbri‘s SpecGen version 5.
- [stardog-groovy](https://github.com/stardog-union/stardog-groovy)
- [stardog-ubuntu-scripts](https://github.com/semantalytics/stardog-ubuntu-scripts)
- [stardog.js](https://github.com/stardog-union/stardog.js)
- [StaTIX](https://github.com/eXascaleInfolab/StaTIX) - Statistical Type Inference (both fully automatic and semi supervised) for RDF datasets.
- [SWRL.js](https://github.com/mterdjimi/SWRL.js) - A SWRL parser for Javascript.
- [swrlapi](https://github.com/protegeproject/swrlapi) - The SWRLAPI is a Java API for working with the OWL-based SWRL rule and SQWRL query languages. It includes graphical tools for editing and executing rules and queries.
- [SWRLRulesToOWLAxioms](https://github.com/dcarralma/SWRLRulesToOWLAxioms) - Implementation of a procedure to transform SWRL rules into equivalent OWL axioms.
- [tac](https://github.com/magnetik/tac) - Triple access control.
- [thedatatank](http://thedatatank.com)
- [TrOWL](https://github.com/TrOWL) - Tractable OWL 2 Reasoning Infrastructure
- [turtle-in-html](https://github.com/alangrafu/turtle-in-html) - Bookmark to visualize RDF embedded in HTML as Turtle.
- [umls2rdf](https://github.com/ncbo/umls2rdf) - These python scripts connect to the Unified Medical Language System (UMLS) database and translate the ontologies into RDF/OWL files. This is part of the BioPortal project.
- [vocbench](http://vocbench.uniroma2.it/)
- [vocol](https://github.com/vocol/vocol) - An integrated environment to support collaborative ontology / vocabulary development in distributed settings.
- [vocol](https://github.com/vocol/vocol) - An integrated environment to support collaborative ontology / vocabulary development in distributed settings.
- [vsb](https://github.com/leipert/vsb) - Visual SPARQL Builder - Model SPARQL-Select-Queries in a browser https://leipert.github.io/vsb/
- [vss-ontology](https://github.com/klotzbenjamin/vss-ontology) - Design of the Vehicle Signal Ontology VSSo and example of use with SOSA/SSN and STEP.
- [wordnet-lemon-to-w3c](https://github.com/jimregan/wordnet-lemon-to-w3c)
- [wsml2reasoner](http://tools.sti-innsbruck.at/wsml2reasoner/) - a highly modular framework that combines various validation, normalization and transformation algorithms that enable the translation of ontology descriptions in WSML to the appropriate syntax of several underlying reasoning engines.
- [xodx](https://github.com/AKSW/xodx) - An implementation of Semantic Pingback and PuSH for a DSSN.
- [yarrrml-parser](https://github.com/RMLio/yarrrml-parser) - A YARRRML parser library and CLI in Javascript.
- http://eventkg.l3s.uni-hannover.de/
- http://ld-r.org
- http://rml.io/yarrrml/
- http://sage.univ-nantes.fr
- http://www.linklion.org/portal/
- https://dvcs.w3.org/hg/rdf/raw-file/default/rdf-json/index.html
- https://github.com/stkenny/grefine-rdf-extension/releases/tag/v1.1.0
- https://metacpan.org/release/KJETILK/AtteanX-Store-SPARQL-0.012
