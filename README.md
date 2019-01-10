
# Awesome Semantic Web [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of various semantic web and linked data resources.

## Contents

- [Standards](#standards)
- [Serialization](#serialization)
- [Datatypes](#datatypes)
- [Companies](#companies)
- [Databases](#databases)
- [Ecosystem](#ecosystem)
- [Knowledge Graph Management](#knowledge-graph-management)
- [SPARQL Implementations](#sparql-implementations)
  - [Streaming SPARQL](#streaming-sparql)
  - [Federated SPARQL](#federated-sparql)
  - [SPARQL Applications](#sparql-applications)
  - [Linked Data Platform (LDP)](#linked-data-platform-ldp)
- [Web Annotations](#web-annotations)
- [Mapping](#mapping)
- [Ontologies](#ontologies)
- [Books](#books)
- [Ontology Development](#ontology-development)
- [Reasoners](#reasoners)
- [Benchmarks](#benchmarks)
- [Programming](#programming)
  - [Java](#java)
  - [Python](#python)
  - [C](#c)
  - [JavaScript](#javascript)
  - [C\#](#c-1)
  - [Go](#go)
  - [PHP](#php)
  - [Clojure](#clojure)
  - [Scala](#scala)
  - [Groovy](#groovy)
  - [R](#r)
  - [Ruby](#ruby)
  - [Swift](#swift)
  - [ObjectiveC](#objectivec)
  - [Prolog](#prolog)
  - [Perl](#perl)
  - [Haskell](#haskell)
  - [OCamel](#ocamel)
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
- [WebID](#webid)
- [Misc](#misc)
- [Industry](#industry)
- [Jobs](#jobs)

## Standards

- [XSD Datatypes](https://www.w3.org/2011/rdf-wg/wiki/XSD_Datatypes)

### RDF

- [RDF 1.1 Primer](https://www.w3.org/TR/rdf11-primer/)
- [RDF 1.1 Semantics](https://www.w3.org/TR/rdf11-mt/)
- [RDF 1.1 Concepts and Abstract Syntax](https://www.w3.org/TR/rdf11-concepts/)
- [RDF 1.1: On Semantics of RDF Datasets](https://www.w3.org/TR/rdf11-datasets/)

### RDFS

- [RDF Schema 1.1](https://www.w3.org/TR/rdf-schema/)

### OWL

- [OWL 2 Web Ontology Language Document Overview](https://www.w3.org/TR/owl-overview/)
- [OWL 2 Web Ontology Language Primer](https://www.w3.org/TR/owl-primer/)
- [manchester](https://www.w3.org/2007/OWL/draft/ED-owl2-manchester-syntax-20081128/)
- [manchester-syntax-owl](https://github.com/rollxx/manchester-syntax-owl2)

### SHACL

- [Shapes Constraint Language](https://www.w3.org/TR/shacl/)

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

### Linked Data Fragments (LDF)

- [Linked Data Fragments](http://linkeddatafragments.org)

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

### Data Cube extensions/

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

## Datatypes

- [Supporting Arbitrary Custom Datatypes in RDF and SPARQL](http://www.maxime-lefrancois.info/research/lindt/)
- [QUDT](http://www.qudt.org)

## Companies

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

## Databases

$ - Proprietary  
OS - OpenSource  
F - Free  

- [Jena TDB](http://jena.apache.org/documentation/tdb/index.html) - (OS).
- [Ontotext GraphDB™](http://graphdb.ontotext.com/) - ($/F).
- [Halyard](https://github.com/Merck/Halyard) - (OS).
- [Stardog](http://stardog.com) - ($/F).
- [Strabon](http://www.strabon.di.uoa.gr/)
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
- [Parliament](http://parliament.semwebcentral.org/) - (OS).
- [wallix/triplestore](https://github.com/wallix/triplestore) - (OS) Nifty library written in Go-Lang.
- [SANSA](http://sansa-stack.net/) - (OS).
- [hbase-rdf](https://github.com/castagna/hbase-rdf) - (OS).
- [Anzograph](https://www.cambridgesemantics.com/product/anzograph/)
- [CumulusRDF](https://github.com/cumulusrdf/cumulusrdf)
- [Sempala](https://github.com/aschaetzle/Sempala)
- [TriplePlace](https://github.com/white-gecko/TriplePlace) - Light weight and flexible Triple Store for Android.
- [Node-Quadstore](https://beautifulinteractions.github.io/node-quadstore/) - (OS) A LevelDB-backed graph database for Node.js supporting quads, SPARQL queries and the RDF/JS interface.
- [KGRAM](http://wimmics.inria.fr/corese) - (OS).
- [luposdate](https://github.com/luposdate/luposdate) - (OS) Semantic Web database.
- [wallix/triplestore](https://github.com/wallix/triplestore) - Nifty library to manage, query and store RDF triples.
- [levelgraph](https://github.com/levelgraph/levelgraph) - (OS) Graph database JS style for Node.js and the Browser.
- [Oxford Semantic RDFox](https://www.oxfordsemantic.tech) - ($) Horizontly scalalbe in-memory triple store with parallel Datalog reasoning.
- [gStore](https://github.com/pkumod/gStore) - (OS).

### Academic

- [TripleRush](https://github.com/uzh/triplerush) - (OS).
- [Corese](http://wimmics.inria.fr/corese) - (OS).
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

## Ecosystem

### Conferences

- [International Semantic Web Conference (ISWC 2019)](http://iswc2019.semanticweb.org)
- [European Semantic Web Conference (ESWC 2019)](https://2019.eswc-conferences.org)

### Blogs

- [Bob DuCharme's weblog technology for representing and linking information](http://www.snee.com/bobdc.blog/)
- [Planet RDF](http://planetrdf.com)
- [Jörn's Blog](https://joernhees.de/blog/)

### Podcasts

TODO

### Meetups

TODO

### Groups

- [RDF-DEV](https://www.w3.org/community/rdf-dev/) - RDF-DEV COMMUNITY GROUP.
- [w3c semantic web](https://lists.w3.org/Archives/Public/semantic-web/)
- [JSON-LD Working Group](https://www.w3.org/2018/json-ld-wg/)
- [w3c activities](https://www.w3.org/Consortium/activities)

### Academic Journals

- [Semantic Web Journal](http://www.semantic-web-journal.net/)
- [Journal of Web Semantics](https://www.journals.elsevier.com/journal-of-web-semantics)
- [International Journal of Web and Semantic Technology](http://www.airccse.org/journal/ijwest/ijwest.html)

### Research Institutions

- [The Smart Data Analytics (SDA)](http://sda.tech/) - Research group, Institute for Computer Science at the University of Bonn, the Fraunhofer Institute for Intelligent Analysis and Information Systems (IAIS) and the Institute for Applied Computer Science Leipzig.
- [Agile Knowledge Engineering and Semantic Web (AKSW)](http://aksw.org) - The Research Group Agile Knowledge Engineering and Semantic Web (AKSW) is hosted by the Chair of Business Information Systems (BIS) of the Institute of Computer Science (IfI) / University of Leipzig as well as the Institute for Applied Informatics (InfAI).
- [University of Zurich Dynamic and Distributed Information Systems Group](http://www.ifi.uzh.ch/en/ddis.html)
- [WESO](http://www.weso.es/) - WESO is a research group at the University of Oviedo founded in 2004.
- [Max Planck Institute for Informatics](https://www.mpi-inf.mpg.de/departments/databases-and-information-systems/) - Department D5 of the Max Planck Institute for Informatics.
- [DICE: Data Science Group](http://dice.cs.uni-paderborn.de/about/) - Universität Paderborn.
- [Ontology Engineering Group (OEG)](http://www.oeg-upm.net/) - The Ontology Engineering Group (OEG) is based at the Computer Science School at Universidad Politécnica de Madrid (UPM).
- [Knowledge Representation and Reasoning Group (KRR)](https://krr.cs.vu.nl/) - Research group is based at the Vrije Universiteit Amsterdam (VU).

## Knowledge Graph Management

$ - Proprietary  
OS - OpenSource  

- [Metaphacts](http://metaphacts.com) - ($) End-to-end platform to create and utilize enterprise knowledge graphs.
- [OntoWiki](https://github.com/AKSW/OntoWiki) - (OS) Semantic data wiki as well as Linked Data publishing engine.
- [GNOSS-Sherlock](https://www.gnoss.com/en/semantic-framework/knowledge-graph-management) - ($) Cognitive Intelligence tool for machines to understand us.

## SPARQL Implementations

### Streaming SPARQL

- [CSPARQL-engine](https://github.com/streamreasoning/CSPARQL-engine)
- [Triplewave](https://github.com/streamreasoning/TripleWave)
- [morph-streams](https://github.com/jpcik/morph-streams)
- [Katts](https://github.com/uzh/katts)
- [WAVES](https://www.waves-rsp.org/)
- [Strider](https://github.com/renxiangnan/strider)
- [cqels](https://github.com/KMax/cqels)
- [morph](https://github.com/jpcik/morph) - Sparql-stream sensor queries.
- [morph-web](https://github.com/jpcik/morph-web)
- [sepa](https://github.com/arces-wot/SEPA) - A JAVA implementation of the SPARQL Event Processing Architecture including the engine, APIs and tools.

### Federated SPARQL

ACTIVE

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

### SPARQL Applications

- [sparqlab](https://github.com/jindrichmynarz/sparqlab) - Lab for exercising SPARQL.
- [SNORQL](https://github.com/kurtjx/SNORQL) - Ajaxy front-end for exploring triple stores.
- [d3-sparql](https://github.com/zazuko/d3-sparql/) - Query a SPARQL endpoint with a SELECT query and get the data ready to be used with d3js
- [d3sparql](https://github.com/ktym/d3sparql) - JavaScript library for executing SPARQL query and transforming resulted JSON for visualization in D3.js.
- [jdbc4sparql](https://github.com/Claudenw/jdbc4sparql) - A JDBC driver that takes data from SPARQL endpoints or RDF graphs.
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

### Linked Data Platform (LDP)

- [fedora](https://duraspace.org/fedora/) - Repository platform with native linked data support.
- [warp](https://github.com/linkeddata/warp) - Warp an LDP file manager.
- [Marmotta](https://github.com/apache/marmotta) - Apache linked data platform implementation.
- [Elda](https://github.com/epimorphics/elda) - Linked data platform from Epimorphics.
- [LDP4j](https://github.com/ldp4j/ldp4j)
- [gold](https://github.com/linkeddata/gold) - Linked Data server for Go.
- [CarbonLDP](https://github.com/CarbonLDP)
- [trellis](https://github.com/trellis-ldp/trellis)

## Web Annotations

- [anno4j](https://github.com/anno4j/anno4j)
- [annotation model](https://www.w3.org/TR/annotation-model/)

## Mapping

- [any2rdf](https://github.com/esbranson/any2rdf)
- [triplify](https://github.com/pebbie/triplify)
- [pyrdb2rdf](https://github.com/nisavid/pyrdb2rdf)
- [xsparql](https://www.w3.org/Submission/xsparql-language-specification/)

### Geo

- [geometry2rdf](https://github.com/boricles/geometry2rdf)
- [TripleGeo](https://github.com/GeoKnow/TripleGeo) - TripleGeo utility for converting geospatial data into triples.

### Excel

- [TabLinker](https://github.com/Data2Semantics/TabLinker)
- [xlwrap](https://github.com/sidewinderlabs/xlwrap)

### CSV/Tabular

- [guide-o-matic](https://github.com/baskaufs/guid-o-matic) - Xquery scripts to convert fielded text (CSV) files to RDF serialized as XML, Turtle, and JSON-LD.
- [COW](https://github.com/CLARIAH/COW) - CSV On the Web (CSVW) converter.
- [CSV2RDF](https://github.com/clarkparsia/csv2rdf) - CSV to RDF mapper.
- [csv2rdf](https://github.com/notruthless/csv2rdf)
- [csv2rdf4lod-automation](https://github.com/timrdf/csv2rdf4lod-automation)
- [tarql-component](https://github.com/opencube-toolkit/tarql-component)
- [tarql](https://github.com/tarql/tarql)

### Object to RDF Mapping

- [Empire](https://github.com/mhgrove/Empire/)
- [Pinto](https://github.com/stardog-union/pinto)
- [Som(m)er](https://github.com/bblfish/sommer)
- [jennabean](https://code.google.com/p/jenabean/)
- [Alibaba](https://bitbucket.org/openrdf/alibaba)
- [rdfbeans](http://rdfbeans.sourceforge.net/)
- [surfrdf](https://github.com/cosminbasca/surfrdf) - SuRF: a python Object RDF Mapper (ORM).
- [jtriple](https://github.com/konradreiche/jtriple) - A Java object model binding for RDF.

### RDB to RDF

- [d2rq](https://github.com/d2rq/d2rq) - Database to RDF mapping engine and SPARQL server.
- [Sparqlify](https://github.com/AKSW/Sparqlify) - Sparql -> SQL Rewriter enabling virtual RDB -> RDF mappings.
- [Sparqlify-Extendsions](https://github.com/AKSW/Sparqlify-Extensions) - Extension projects for Sparqlify.
- [quetzal](https://github.com/Quetzal-RDF/quetzal) - SPARQL to SQL translation engine for multiple backends, such as DB2, PostgreSQL and Apache Spark.

### XML

- [ontmalizer](https://github.com/srdc/ontmalizer) - Comprehensive transformations of XML Schemas (XSD) and XML data to RDF/OWL automatically.

#### R2RML

- [R2RML-Parser](https://github.com/nkons/r2rml-parser) - An R2RML implementation that can export relational database contents as RDF graphs.
- [Morph-RDB](https://github.com/oeg-upm/morph-rdb) - An R2RML processor.
- [MusicBrainz-R2RML](https://github.com/LinkedBrainz/MusicBrainz-R2RML) - R2RML mappings for the MusicBrainz schema.
- [ontop](https://github.com/ontop/ontop) - Ontop is a platform to query relational databases as Virtual RDF Graphs using SPARQL. It's fast and is packed with features.
- [db2triples](https://github.com/antidot/db2triples) - Antidot implementations of R2RML and Direct Mapping specifications.
- [ADAPT-R2RML](https://opengogs.adaptcentre.ie/debruync/r2rml)
- [R2RML-api](https://github.com/R2RML-api/R2RML-api)
- [R2RML-kit](https://github.com/d2rq/r2rml-kit)
- [Juma](https://opengogs.adaptcentre.ie/crottija/juma-r2rml/) - Juma, jigsaw puzzles for representing mapping, is a method that applies the block metaphor to mapping languages.
- [pyrdb2rdf](https://github.com/nisavid/pyrdb2rdf) - A Python library for RDB2RDF Direct Mapping and R2RML.
- [sparqlmap](https://github.com/tomatophantastico/sparqlmap)
- [rdf2rml](https://github.com/VladimirAlexiev/rdf2rml) - R2RML Generation from simple examples.
- [ultrawrap](https://capsenta.com/)

##### xR2RML

- [morph-xr2rml](https://github.com/frmichel/morph-xr2rml)
- [XR2RML](https://github.com/djimloic/XR2RML)

##### R2RML-f

- [paper](http://events.linkeddata.org/ldow2016/papers/LDOW2016_paper_14.pdf)
- [Adapt R2RML](https://opengogs.adaptcentre.ie/debruync/r2rml)

#### RML

- [RML](https://github.com/RMLio) - RDF Mapping language for mapping JSON, CSV and XML to RDF.
- [CARML](https://github.com/carml/carml) - CARML RML engine for mapping CSV, XML and JSON files to RDF

#### Other RDF Mappings

- [sparql-generate](https://github.com/sparql-generate/sparql-generate)
- [any23](https://any23.apache.org/)

## Ontologies

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
- [PROV-O](https://www.w3.org/TR/prov-o/) - Represent provenance information.

### Common

- [foaf](http://www.foaf-project.org/) - Friend of a Friend (FOAF) ontology.

### Community

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
- [VIVO ISF](https://wiki.duraspace.org/display/VTDA/VIVO-ISF+Ontology) - Researchers and the full context in which they work.

### Educational

- [MMOntologies](https://github.com/gatemezing/MMOntologies) - Multimedia ontologies studied for the paper "The Landscape of Multimedia Ontologies in the last Decade".
- [Wine](https://www.quora.com/What-is-wine-ontology) - Wine Ontology is a popular example of an OWL ontology.
- [Pizza](http://owl.cs.manchester.ac.uk/publications/talks-and-tutorials/protg-owl-tutorial/) - A step-by-step guide to modelling in OWL using the popular Protégé OWL tools.

## Books

- [Linked Data](https://www.manning.com/books/linked-data)
- [Explorer's Guide to the Semantic Web](https://www.manning.com/books/explorers-guide-to-the-semantic-web)
- [Semantic Web Programming](https://www.wiley.com/en-us/Semantic+Web+Programming-p-9781118080603)
- [Semantic Web for the Working Ontologist](http://workingontologist.org/)
- [Programming the Semantic Web](http://shop.oreilly.com/product/9780596153823.do)
- [Building Ontologies with Basic Formal Ontology](https://mitpress.mit.edu/books/building-ontologies-basic-formal-ontology)
- [Structures for Organizing Knowledge: Exploring Taxonomies, Ontologies, and Other Schema](https://www.amazon.com/Structures-Organizing-Knowledge-Taxonomies-Ontologies/dp/1555706991)
- [Validating RDF Data](http://book.validatingrdf.com/)

## Ontology Development

- [protégé](http://protege.stanford.edu) - Ontology editor and framework for building intelligent systems.
- [OntoVerbal](https://github.com/TheOntologist/OntoVerbal) - OntoVerbal is a Protege 4.2 plugin that generates natural language descriptions for classes for an ontology written in OWL.

## Reasoners

- [Pellet](https://github.com/stardog-union/pellet)
- [openllet](https://github.com/Galigator/openllet)
- [FaCT++](https://github.com/ethz-asl/libfactplusplus)
- [HermiT](http://www.hermit-reasoner.com/)
- [ELK](https://github.com/liveontologies/elk-reasoner)
- [OWL-RL](https://github.com/RDFLib/OWL-RL)
- [RacerPro](https://franz.com/agraph/racer/)
- [Manchester List of Reasoners](http://owl.cs.manchester.ac.uk/tools/list-of-reasoners/)
- [elephant-reasoner](https://github.com/sertkaya/elephant-reasoner)
- [HyLAR](https://github.com/ucbl/HyLAR-Reasoner)
- [ruby-rdf/rdf-reasoner](https://github.com/ruby-rdf/rdf-reasoner)
- [pellet](https://github.com/lepfhty/pellet) - Pallet reasoner (old version).

## Benchmarks

- [Berlin SPARQL Benchmark (BSBM)](http://wifo5-03.informatik.uni-mannheim.de/bizer/berlinsparqlbenchmark/)
- [Lehigh University Benchmark (LUBM)](http://swat.cse.lehigh.edu/projects/lubm/)
- [IGUANA](https://github.com/dice-group/IGUANA)
- [dice-group/triplestore-benchmarks](https://web.archive.org/web/20180627155808/https://github.com/dice-group/triplestore-benchmarks) - An Evaluation of Triplestore Benchamrks.
- [RdfStoreBenchmarking](https://www.w3.org/wiki/RdfStoreBenchmarking)
- [Hobbit](http://project-hobbit.eu/) - Holistic Benchmarking of Big Linked Data.
- [SP2Bench](http://dbis.informatik.uni-freiburg.de/index.php?project=SP2B)
- [IGUANA](https://github.com/AKSW/IGUANA) - IGUANA is a benchmark execution framework for triple stores.
- [SRBench](https://github.com/jpcik/srbench) - A streaming sparql benchmark.

## Programming

### Java

- [RDF4J](http://rdf4j.org)
- [Jena](http://jena.apache.org)
- [commons-rdf](http://commons.apache.org/proper/commons-rdf/)
- [foafssl-java](https://github.com/bblfish/foafssl-java)
- [soarql-dl-api](https://github.com/protegeproject/sparql-dl-api) - A query engine for SPARQL-DL.
- [nxparser](https://github.com/nxparser/nxparser) - Java parsers for different RDF serialisations + API + tools + JAX-RS integration.

### Python

- [RDFlib](https://github.com/RDFLib/rdflib) - Pythonic RDF API.
- [SPARQLWrapper](https://github.com/RDFLib/sparqlwrapper) - A wrapper for a remote SPARQL endpoint.
- [sparql-client](https://github.com/eea/sparql-client) - Python API to query a SPARQL endpoint.
- [RdfAlchemy](https://github.com/gjhiggins/RDFAlchemy)
- [Fuxi](http://code.google.com/p/fuxi/) - Bi-directional logical reasoning system for the semantic web.
- [pySHACL](https://github.com/RDFLib/pySHACL) - A Python validator for SHACL.
- [PyShEx](https://github.com/hsolbrig/PyShEx) - ShEx interpreter for ShEx 2.0.
- [ORDF](http://ordf.org)
- [Django-rdf](http://code.google.com/p/django-rdf/) - An RDF engine for Django projects.
- [Djubby](https://github.com/wikier/djubby) - Linked Data frontend for SPARQL endpoints for Django.
- [SuRF](http://packages.python.org/SuRF/)
- [sparta](https://github.com/mnot/sparta/) - Simple API for RDF.
- [rdftools](https://github.com/cosminbasca/rdftools) - Simple collection of python RDF tools.
- [cysparql](https://github.com/cosminbasca/cysparql) - CySparql is a python wrapper over the excellent rasqal RDF library for parsing SPARQL queries.

### C

- [serd](https://github.com/drobilla/serd) - Lightweight C library for RDF syntax.
- [librdf](https://github.com/dajobe/librdf) - Redland librdf RDF API and triple stores.
- [raptor](https://github.com/dajobe/raptor) - Redland Raptor RDF syntax library.
- [rasqal](https://github.com/dajobe/rasqal) - Redland Rasqal RDF Query Library.

### JavaScript

- [js3](https://github.com/webr3/js3)
- [rdfstore-js](https://github.com/antoniogarrote/rdfstore-js)
- [rdf-ext](https://github.com/rdf-ext/rdf-ext)
- [N3.js](https://github.com/RubenVerborgh/N3.js)
- [Jessa](https://www.npmjs.com/package/jassa)
- [RDFJS](https://github.com/rdfjs) - Github Organization that maintains modern JavaScript RDF libraries based on open, maintained standards
- [rdf.js](https://github.com/webr3/rdf.js)
- [rdflib.js](https://github.com/linkeddata/rdflib.js) - Linked Data API for JavaScript.
- [sparks](https://github.com/sparksrdf/sparks) - Sparks is a set of JavaScript libraries designed for simplifying the access to RDF data.
- [SPARQL.js](https://github.com/RubenVerborgh/SPARQL.js/) - A parser for the SPARQL query language in JavaScript.
- [sparqlalgebrajs](https://github.com/joachimvh/SPARQLAlgebra.js) - SPARQL to SPARQL Algebra converter.
- [RDForms](https://rdforms.org) - Construct form-based RDF editors in a web environment.

### C\#

- [dotNetRDF](https://github.com/dotnetrdf/dotnetrdf)
- [RDFSharp](https://github.com/mdesalvo/RDFSharp)

### Go

- [rdf2go](https://github.com/deiu/rdf2go) - Native golang library for RDF.
- [knakk/rdf](https://github.com/knakk/rdf) - RDF library for Go.

### PHP

- [EasyRdf](http://www.easyrdf.org/)
- [semsol](https://github.com/semsol/arc2/wiki)
- [PHP-SPARQL-Lib](https://github.com/cgutteridge/PHP-SPARQL-Lib)
- [Graphite](http://graphite.ecs.soton.ac.uk/)
- [sparqllib](http://graphite.ecs.soton.ac.uk/sparqllib/)

### Clojure

- [grafter](https://github.com/Swirrl/grafter) - Linked Data & RDF Manufacturing Tools in Clojure.
- [kr](https://github.com/drlivingston/kr) - Clojure API for RDF and SPARQL - provides consistent access to APIs including Jena and Sesame.
- [clj-plaza](https://github.com/antoniogarrote/clj-plaza) - Clojure rdf framework.
- [seabass](https://github.com/ryankohl/seabass) - A library for working with RDF with Jena in Clojure.

### Scala

- [banana-rdf](https://github.com/banana-rdf/banana-rdf) - A library for RDF, SPARQL and Linked Data technologies in Scala.
- [jvmrdftools](https://github.com/cosminbasca/jvmrdftools)
- [SANSA-RDF](https://github.com/SANSA-Stack/SANSA-RDF) - Library to read RDF files into Spark or Flink.

### Groovy

- [groovyrdf](https://github.com/angelo-v/groovyrdf)

### R

- [rrdf](https://github.com/egonw/rrdf)

### Ruby

- [ruby-rdf](http://ruby-rdf.github.io)

### Swift

- [swift-sparql-syntax](https://github.com/kasei/swift-sparql-syntax) - SPARQL 1.1 Parser.
- [URITemplate](https://github.com/kasei/URITemplate) - Swift implementation of URI Template ([RFC6570](https://tools.ietf.org/html/rfc6570)).
- [swift-serd](https://github.com/kasei/swift-serd) - Swift package wrapper for the [Serd RDF library](http://drobilla.net/software/serd).
- [kineo](https://github.com/kasei/kineo) - A SPARQL endpoint and quadstore written in Swift.
- [swift-hdt](https://github.com/kasei/swift-hdt) - An [HDT](http://www.rdfhdt.org/) RDF Parser.

### ObjectiveC

- [SPARQLKit](https://github.com/kasei/SPARQLKit) - An implementation of the SPARQL 1.1 query language in Objective-C.

### Prolog

- [SWI-Prolog Semantic Web Library](http://www.swi-prolog.org/pldoc/doc_for?object=section(%27packages/semweb.html%27))

### Perl

- [Attean](https://metacpan.org/pod/Attean)
- [RDF::Trine](https://metacpan.org/pod/RDF::Trine)

### Haskell

- [rdf4h](https://github.com/robstewart57/rdf4h)
- [swish](https://bitbucket.org/doug_burke/swish/wiki/Home)
- [hsparql](https://github.com/robstewart57/hsparql)

### OCamel

- [ocaml-rdf](https://www.good-eris.net/ocaml-rdf/) - Manipulate RDF graphs and execute Sparql queries.

## Editors

### VIM

- [sparql.vim](https://github.com/vim-scripts/sparql.vim) - SPARQL syntax highlighting.
- [vim-sparql](https://github.com/Omer/vim-sparql)
- [semweb.vim](https://github.com/seebi/semweb.vim)

### Emacs

- [sparql-mode](https://github.com/ljos/sparql-mode)

### IntelliJ

- [sparql4idea](https://github.com/mattnathan/sparql4idea) - SPARQL language plugin for IntelliJ IDEA.

### Visual Studio Code

- [Stardog RDF Grammars](https://marketplace.visualstudio.com/items?itemName=stardog-union.stardog-rdf-grammars)

### TextMate

- [sparql/turtle extension](https://github.com/peta/turtle.tmbundle)

### Sublime Text 3

- [Turtle and SPARQL syntax highlighter](https://github.com/abcoates/sublime-text-turtle-sparql)

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

## Data Cube

- [QB4ST: RDF Data Cube extensions for spatio-temporal components](https://www.w3.org/TR/qb4st/)
- [The RDF Data Cube Vocabulary](https://www.w3.org/TR/vocab-data-cube/)
- [qb4olap-tools](https://github.com/lorenae/qb4olap-tools)
- [OpenCube-Expander](https://github.com/opencube-toolkit/OpenCube-Expander)
- [OpenCube Toolkit](http://opencube-toolkit.eu/)
- [CubeViz](https://github.com/AKSW/cubeviz.ontowiki)
- [NoSPA-RDF-Data-Cube-Validator](https://github.com/yyz1989/NoSPA-RDF-Data-Cube-Validator)

## Datasets

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

## Tools

- [tawny-owl](https://github.com/phillord/tawny-owl) - Build OWL Ontologies in a Programmatic Environment.
- [Widoco](https://github.com/dgarijo/Widoco)
- [sesame-vocab-builder](https://github.com/tkurz/sesame-vocab-builder) - Sesame Vocab Builder provides a command line tool that allows to create constants for RDF primitives for a given namespace out of RDF ontology files.
- [HydraConsole](https://github.com/lanthaler/HydraConsole)
- [qonsole](https://github.com/epimorphics/qonsole) - A simple console for running SPARQL queries and displaying results.
- [ntcat](https://github.com/cgutteridge/ntcat) - Command line tool for concatenating NTriples documents.
- [ripple](https://github.com/joshsh/ripple) - Semantic Web scripting language.
- [schema_salad](https://github.com/common-workflow-language/schema_salad) - Semantic Annotations for Linked Avro Data.
- [RDFConvert](https://sourceforge.net/projects/rdfconvert/) - RDFConvert is a simple command-line tool for converting RDF file betweeen different syntax formats.
- [How to diff RDF](https://www.w3.org/2001/sw/wiki/How_to_diff_RDF)
- [grlc](https://github.com/CLARIAH/grlc) - Web APIs from SPARQL queries.
- [Openlink Structured Data Sniffer](http://osds.openlinksw.com/) - Browser extension for Google Chrome, Microsoft Edge, Mozilla Firefox, Opera, and Vivaldi that unveils structured metadata embedded within HTML documents and web pages. 
- [ShacShifter](https://github.com/AKSW/ShacShifter) - Shapes Constraint Language (SHACL) to various other format.

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

## Machine Learning

- [LinkedPipes-ETL](https://github.com/linkedpipes/etl) - Linked Data ETL pipeline.
- [gm-sparql](https://github.com/ssrangan/gm-sparql) - Graph Mining Using SPARQL.
- [SANSA-Stack](http://sansa-stack.net) - Scalable Semantic Analytics Stack.
- [tdbloader4](https://github.com/castagna/tdbloader4) - Prototype to show how TDB indexes can be generated using MapReduce.
- [jena-grande](https://github.com/castagna/jena-grande) - Jena Grande is a collection of utilities, experiments and examples on how to use MapReduce, Pig, HBase or Giraph to process data in RDF format.
- [mrlin](https://github.com/mhausenblas/mrlin) - MapReduce processing of Linked Data.
- [infovore](https://github.com/paulhoule/infovore) - RDF-Centric Map/Reduce Framework and Freebase data conversion tool.
- [FOX](https://github.com/AKSW/FOX) - Federated Knowledge Extraction Framework.
- [singal-collect](https://github.com/uzh/signal-collect)
- [Duke](https://github.com/larsga/Duke) - Duke is a fast and flexible deduplication engine written in Java.
- [ODCS](https://github.com/mff-uk/ODCS) - The tool uses data processing pipelines for obtaining, processing, and storing RDF data.
- [etalis](https://github.com/sspider/etalis) - Event Processing SPARQL (EP-SPARQL).
- [graph-pattern-learner](https://github.com/RDFLib/graph-pattern-learner) - Evolutionary Graph Pattern Learner that learns SPARQL queries for a given set of source-target-pairs from an endpoint.

## WebID

- [xwiki](https://github.com/bblfish/xwiki) - Xwiki related code for WebID.
- [solid-spec](https://github.com/solid/solid-spec)
- [webid-demo](https://github.com/digitalbazaar/webid-demo)
- [webid-spec](https://github.com/webid-community/webid-spec)
- [node-webid](https://github.com/magnetik/node-webid)

## Misc

- [LDIF](https://github.com/wbsg/ldif) - Linked Data Integration Framework.
- [swrlapi](https://github.com/protegeproject/swrlapi) - The SWRLAPI is a Java API for working with the OWL-based SWRL rule and SQWRL query languages. It includes graphical tools for editing and executing rules and queries.
- [cp-common-utils](https://github.com/mhgrove/cp-common-utils) - Collection of utilty classes from Clark & Parsia.
- [jena-joseki](https://github.com/tingletech/jena-joseki)
- [stardog-ubuntu-scripts](https://github.com/semantalytics/stardog-ubuntu-scripts)
- [Git2PROV](https://github.com/mmlab/Git2PROV) - Unleash the potential of Git in the new W3C standard for provenance.
- [iqvoc](https://github.com/innoq/iqvoc) - SKOS(-XL) Vocabulary Management System for the Semantic Web.
- [hydra-java](https://github.com/dschulten/hydra-java)
- [IntervalServer](https://github.com/epimorphics/IntervalServer)
- [TabLinker](https://github.com/Data2Semantics/TabLinker) - Supervised Excel/CSV to RDF Converter.
- [jdbc-for-rdf3x](https://github.com/dbiir/jdbc-for-rdf3x)
- [rdf3x_path](https://github.com/agubichev/rdf3x_path) - RDF3X with path queries.
- [jqudt](https://github.com/egonw/jqudt) - Java library for working with the QUDT ontology and data using it.
- [JenaSecurity](https://github.com/Claudenw/JenaSecurity) - Security (Permissions) wrapper around Jena RDF implementation.
- [specgen](https://github.com/specgen/specgen) - Modified, extended and more generalized version of Danbri‘s SpecGen version 5.
- [cassa](https://github.com/heuer/cassa) - SPARQL 1.1 Graph Store HTTP Protocol implementation with plugable backends.
- [graphity-browser](https://github.com/AtomGraph/Web-Client) - Generic Linked Data browser.
- [keygenapp](https://github.com/bblfish/keygenapp)
- [owlapitools](https://github.com/owlcs/owlapitools) - Set of independent add-ons for OWL API.
- [LD-FusionTool](https://github.com/mifeet/LD-FusionTool)
- [fox-ui](https://github.com/Data2Semantics/fox-ui)
- [prefix.cc](https://github.com/cygri/prefix.cc) - Source code to the prefix.cc website.
- [LSD-Dimensions](https://github.com/albertmeronyo/LSD-Dimensions) - All dimension values of Linked Statistical Data.
- [prissma](https://github.com/lukostaz/prissma) - Context-Aware Adaptation for Linked Data.
- [fox-java](https://github.com/renespeck/fox-java)
- [fox-py](https://github.com/earthquakesan/fox-py)
- [ORE](https://github.com/AKSW/ORE)
- [signal-collect-torque](https://github.com/uzh/signal-collect-torque)
- [redland-bindings](https://github.com/dajobe/redland-bindings)
- [mediation](https://github.com/correndo/mediation) - Jena based framework to implement ontological mediation of SPARQL queries.
- [owl-functional-syntax-axiom-parser](https://github.com/dfleischhacker/owl-functional-syntax-axiom-parser)
- [SemanticPingback](https://github.com/AKSW/SemanticPingback)
- [json-ld-macros](https://github.com/antoniogarrote/json-ld-macros)
- [tac](https://github.com/magnetik/tac) - Triple access control.
- [dbpedia-extension](https://github.com/sparkica/dbpedia-extension)
- [grefine-rdf-extension](https://github.com/OpenRefine/grefine-rdf-extension)
- [LD-FusionTool](https://github.com/mifeet/LD-FusionTool)
- [xodx](https://github.com/AKSW/xodx)
- [morph-starter](https://github.com/jpcik/morph-starter)
- [sesametools](https://github.com/joshsh/sesametools)
- [DEER](https://github.com/GeoKnow/DEER)
- [levelgraph-jsonld](https://github.com/mcollina/levelgraph-jsonld)
- [owlapi](https://github.com/owlcs/owlapi) - The OWL API is a Java API for creating, manipulating and serialising OWL Ontologies.
- [LODGrefine](https://github.com/sparkica/LODGrefine)
- [stardog.js](https://github.com/stardog-union/stardog.js)
- [stardog-groovy](https://github.com/stardog-union/stardog-groovy)
- [HydraClient](https://github.com/lanthaler/HydraClient)
- [cp-openrdf-utils](https://github.com/mhgrove/cp-openrdf-utils) - Utility classes for working with the OpenRdf API.
- [linked-csv](https://github.com/JeniT/linked-csv) - A souped-up CSV-based data format.
- [balloon](https://github.com/schlegel/balloon) - A tool-suite for Linked Data consumption. balloon aims in offering public services and tools to take advantage of the semantic web with less effort. The basic motivation is to establish a foundation for Linked Data as a Service (LDaaS).
- [Processor](https://github.com/AtomGraph/Processor) - Generic Linked Data processor and server. Apache License.
- [grlc](https://github.com/CLARIAH/grlc) - Translates public SPARQL queries into Linked Data APIs automatically.
- [basil](https://github.com/the-open-university/basil) - Building Apis SImpLy from sparql endpoints.
- [lodmill](https://github.com/lobid/lodmill) - Blend, grind, and enjoy LOD – fresh from the mill!
- [module-extractor](https://github.com/rsgoncalves/module-extractor) - Java-based module extractor for OWL ontologies.
- [iRap](https://github.com/EIS-Bonn/iRap) - iRap - Interest-based RDF update propagation framework.
- [turtle-in-html](https://github.com/alangrafu/turtle-in-html) - Bookmark to visualize RDF embedded in HTML as Turtle.
- [linked-csv-browser](https://github.com/theodi/linked-csv-browser)
- [semargl](https://github.com/semarglproject/semargl) - Highly performant, lightweight framework for linked data processing. Supports RDFa, JSON-LD, RDF/XML and plain text formats, runs on Android and GAE, provides integration with Jena, Sesame and Clerezza.
- [wordnet-lemon-to-w3c](https://github.com/jimregan/wordnet-lemon-to-w3c)
- [hyrise](https://github.com/hyrise/hyrise)
- [owlconvert](https://github.com/camwebb/owlconvert) - Simple OWL format converter based on OWLAPI.
- [rabel](https://github.com/linkeddata/rabel) - Program for reading and writing linked data in various formats.
- [csvw-template](https://github.com/edsu/csvw-template) - Document the semantics of your csv file.
- [jsonld-java](https://github.com/jsonld-java/jsonld-java) - JSON-LD implementation for Java.
- [Luzzu](https://github.com/Luzzu/Framework/) - A scalable and extensible Linked Data quality assessment framework.
- [odmtp-tpf](https://github.com/benjimor/odmtp-tpf) - Triple pattern matching over non-RDF datasources with inference .
- [shacl](https://github.com/TopQuadrant/shacl) - SHACL API in Java based on Apache Jena.

## Industry
### Health
- [optum](https://www.optum.com) - known to use semantic graphs (marklogic).

## Jobs
