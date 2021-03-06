
KG study group - from theory to code
====================================

### Knowledge Graph Study Group, Sp ’21.  

**Meeting notes, etc.**: 
https://docs.google.com/spreadsheets/d/1LvoWFUuum93yPZtQC-cm__2woM2mJwAgdD4ZBnVI-Uc/edit#gid=1194089826

**Course link**: https://open.hpi.de/courses/knowledgegraphs2020

### Roster
**Week 1: Knowledge Graphs in the Web of Data**
- Meeting date: March 12, 2021

**Week 2: Basic Semantic Technologies**
- Meeting date: March 19, 2021
- Demo/Share-out: Find examples of RDFa/Turtle syntax in the wild or from work
- [Food Ontology OWL syntax](https://raw.githubusercontent.com/FoodOntology/foodon/master/foodon.owl)
- [Food Ontolgoy Turtle syntax](https://www.bbc.com/ontologies/fo/1.1.ttl)
- [TerminusDB uses query function relying on Prolog, based on first order logic](https://medium.com/terminusdb/today-we-release-terminusdb-the-database-for-data-people-36cfd3f81d3f)

**Week 3: Querying RDF with SPARQL**
- Meeting date: March 26, 2021
- Demo: SPARQL query examples!
- [DBpedia SPARQL endpoint](https://dbpedia.org/sparql)
- [Wikidata SPARQL endpoint](https://query.wikidata.org/)
- [Step-by-step instructions for setting up Virtuoso](https://docs.google.com/presentation/d/1mWrCK_24Kw869ND60vIFRUUDzy3zx4x5xyQ9bTB0o1w/edit#slide=id.p)
- [Querying Wikidata with SPAQRL for Absolute Beginners (Youtube)](https://www.youtube.com/watch?v=kJph4q0Im98)
- [Marcelo Barbieri's helpful medium posts](https://mbarbieri77.medium.com/)

**Week 4: Knowledge Representation with Ontologies**
- Meeting date: April 2, 2021
- Demo: Glenn will share drafted media ontology; Bob will give overview of OWL.

**Week 5: Knowledge Graph Applications**
- Meeting date: April 9, 2021
- Demo: TBD

**Week 6: Advanced Knowledge Graph Applications**
- Meeting date: April 16, 2021
- Demo: TBD

**What we'll cover next**
- Deep dive on semantic web tool (Bob)
- More TBD!

### Books

**P. Hitzler, M. Krötzsch, S. Rudolph**: Foundations of Semantic Web
Technologies, CRC Press, 2009.    
https://www.semantic-web-book.org/index.html    
**T. Heath, Ch. Bitzer**: Linked Data - Evolving the Web into a Global Data
Space, Morgan & Claypool, 2011.


### Tutorials

**[Data.world SPARQL Tutorial](https://docs.data.world/tutorials/sparql/)**
- excellent beginner tutorial as moves quickly through basics with no confusing pre-amble
- interactive: allows running queries as part of the tutorial against data.world resources
- does not cover relationship to SQL or describe why certain design decisions were made (e.g. why not keep the syntax more similar to SQL?)

**[Apache Jena SPARQL Tutorial](https://jena.apache.org/tutorials/sparql.html)**: more clunky than the first, but moves into more detail of functions such as FILTER

**StarDog Tutorials**
- provides data for free
- examples can be performed in Jena or Rasqal locally (using the sparql or roqet command line utilities to query the data files directly
- Need to add the PREFIXes to the queries (at least the standard rdf and rdfs):
	- [PREFIX rdf](http://www.w3.org/1999/02/22-rdf-syntax-ns#)
	- [PREFIX rdfs](http://www.w3.org/2000/01/rdf-schema#)
- also can use [https://stardog.studio](https://stardog.studio/) for free, datasets already loaded
- [Tutorial 1](https://www.stardog.com/tutorials/getting-started-1) has examples of how to accomplish in SQL; starts off with heavy queries, to show example outputs, and then dissects.
- [OWL Tutorial: New Protege Pizza Tutorial](https://www.michaeldebellis.com/post/new-protege-pizza-tutorial) 
- [OWL Tutorial: OWL 101](https://www.cambridgesemantics.com/blog/semantic-university/learn-owl-rdfs/owl-101/)

### Other Helpful Resources

**Awesome Semantic Web**: A wonderful curated list of semantic/linked data resources:    
https://github.com/semantalytics/awesome-semantic-web/blob/master/README.md

