# What is NoSQL ?
NoSQL databases are non-tabular databases and store data differently than relational tables. NoSQL databases come in a variety of types based on their data model. The main types are document, key-value, wide-column, and graph. They provide flexible schemas and scale easily with large amounts of data and high user loads.

# Overview
* NOSQL database
   * Introduction
   * Types of NOSQL
   * Advantages of NOSQL over Relational
   * Disadvantages of NOSQL over Relational
 * Future prospects for NOSQL
 * Conclusion
 * References

# NOSQL database
When people use the term “NoSQL database,” they typically use it to refer to any non-relational database. Some say the term “NoSQL” stands for “non SQL” while others say it stands for “not only SQL.” Either way, most agree that NoSQL databases are databases that store data in a format other than relational tables.

## Introduction
The problem with relational model is that it has some scalability issues that is performance degrades rapidly as data volumes increases. This led to the development of a new data model i.e. NOSQL. Though the concept of NOSQL was developed a long time ago, it was after the introduction of database as a service (DBaaS) that it gained a prominent recognition. Because of the high scalability provided by NOSQL, it was seen as a major competitor to the relational database model. Unlike RDBMS, NOSQL databases are designed to easily scale out as and when they grow. Most NOSQL systems have removed the multi-platform support and some extra unnecessary features of RDBMS,making them much more lightweight and efficient than their RDMS counterparts. The NOSQL data model does not guarantee ACID properties (Atomicity, Consistency, Isolation and Durability) but instead it guarantees BASE properties (Basically Available, Soft state, Eventual consistency).It is in compliance with the CAP (Consistency, Availability, Partition tolerance) theorem.

## Types
NOSQL can be categorized into 5 types

## 1. Key-Value Store Databases
The key-value data stores are pretty simplistic, but are quiet efficient and powerful model. It has a simple application programming interface (API). A key value data store allows the user to store data in a schema less manner. The data is usually some kind of data type of a programming language or an object. The data consists of two parts, a string which represents the key and the actual data which is to be referred as value thus creating a „key-value‟ pair. These stores are similar to hash tables where the keys are used as indexes, thus making it faster than RDBMS Thus the data model is simple: a map or a dictionary that allows the user to request the values according to the key specified. The modern key value data stores prefer high scalability over consistency. Hence ad-hoc querying and analytics features like joins and aggregate operations have been omitted. High concurrency, fast lookups and options for mass storage are provided by key-value stores. One of the weaknesses of key value data sore is the lack of schema which makes it much more difficult to create custom views of the data.

## 2. Column-Oriented Databases
Column stores in NO SQL are actually hybrid row/column store unlike pure relational column databases. Although it shares the concept of column-by-column storage of columnar databases and columnar extensions to row-based databases, column stores do not store data in tables but store the data in massively distributed architectures. In column stores, each key is associated with one or more attributes (columns). A Column store stores its data in such a manner that it can be aggregated rapidly with less I/O activity. It offers high scalability in data storage. The data which is stored in the database is based on the sort order of the column family.

## 3. Document Store Databases
Document Store Databases refers to databases that store their data in the form of documents. Document stores offer great performance and horizontal scalability options. Documents inside a document-oriented database are somewhat similar to records in relational databases, but they are much more flexible since they are schema less. The documents are of standard formats such as XML, PDF, JSON etc. In relational databases, a record inside the same database will have same data fields and the unused data fields are kept empty, but in case of document stores, each document may have similar as well as dissimilar data. Documents in the database are addressed using a unique key that represents that document. These keys may be a simple string or a string that refers to URI or path. Document stores are slightly more complex as compared to key-value stores as they allow to encase the key- value pairs in document also known as key-document pairs.

## 4. Graph Databases
Graph databases are databases which store data in the form of a graph. The graph consists of nodes and edges, where nodes act as the objects and edges act as the relationship between the objects. The graph also consists of properties related to nodes. It uses a technique called index free adjacency meaning every node consists of a direct pointer which points to the adjacent node. Millions of records can be traversed using this technique. In a graph databases, the main emphasis is on the connection between data. Graph databases provides schema less and efficient storage of semi structured data.. The queries are expressed as traversals, thus making graph databases faster than relational databases. It is easy to scale and whiteboard friendly. Graph databases are ACID compliant and offer rollback support.

## 5. Object Oriented Databases
An object oriented database is a database in which the data or the information to be stored is represented as an object (similar to an object used in the concept of object oriented programming language). Thus object oriented database can be considered as a combination of object oriented programming (OOP) and database principles. Object data store offers all the features of OOP such as data encapsulation, polymorphism and inheritance. The class, objects, and class attributes in such databases are comparable to a table, tuple and columns in a tuple in RDBMS respectively. Each object has an object identifier which can be used to uniquely represent that object. Access to data is faster in case of object oriented databases because object can be directly retrieved using pointers. Object oriented databases makes modern software development processes easier to be agile.

# Advantages of NOSQL over Relational
* Provides a wide range of data models to choose from
* Easily scalable
* Database administrators are not required
* Some of the NOSQL DBaaS providers like Riak and Cassandra are programmed to handle hardware failures
* Faster , more efficient and flexible
* Has evolved at a very high pace

# Disadvantages of NOSQL over Relational
* Immature
* No standard query language
* Some NOSQL databases are not ACID compliant
* No standard interface
* Maintenance is difficult
  
# Future prospects for NOSQL
Although NOSQL has evolved at a very high pace, it still lags behind relational database in terms of number of users. The main reason behind this is that the users are more familiar with SQL while NOSQL databases lack a standard query language. If a standard query language for NOSQL is introduced, it will surely be a game changer. [9] Jing Han; Haihong, E.; Guan Le; Jian Du; , "Survey on NoSQL database," Pervasive Computing and Applications (ICPCA), 2011 6th International Conference on , vol., no., pp.363-366, 26-28 Oct. 2011 doi: 10.1109/ ICPCA.2011.6106531 There are a few DBaaS providers over the cloud like Xeround which works on the hybrid database model, that is, they have the familiar SQL in the frontend and NOSQL in the backend. These databases night not be as fast as a pure NOSQL database but they still provide features of both relational as well as NOSQL databases to the user. Thus a lot of disadvantages of both relational as well as NOSQL databases may be covered up. With a few more advancements in this hybrid architecture the future prospects for NOSQL databases in DBaaS are excellent.

# Conclusion
This paper describes the types of NOSQL databases with definition.This paper also describes the advantages and disadvantages of NOSQL databases and future prospects for NOSQL.

# References
 1. MongoDB https://www.mongodb.com/nosql-explained

 2.  https://www.researchgate.net/publication/302557703_Article_Type_of_nosql_databases_and_its_comparison_with_relational_databases

