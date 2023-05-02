# ESILV-S8-PROTEGE-WEB-DATA

Project: Web Datamining & Semantics

This project was completed by a group of three individuals - Adèle Montoya, Paul Runavot, and Eleonor Kioulou.
The main objective of the project was to design a movie application that followed the Linked Data principles,
where movie instances were described as instances of schema:Movie, represented in a standard vocabulary that any application could process.

The project had several pedagogical objectives, including doing software development using Semantic Web programming frameworks, setting up
and interacting with an RDF database, exploiting multiple sources of heterogeneous data, and presenting information online with rich metadata.

The project consisted of four parts. 
In part one, the group modeled the ontology using the Protégé editor, which modeled movies.
A movie had one or several directors, writers, and actors, and also had a title, one or several genres, a year, a country, and a language.
Actors, directors, and writers were persons, and persons had a gender (male or female), a name, an age, and a nationality.
Movies were scheduled in theaters that had locations.

In part two, the group populated the ontology with individuals such as movies, persons, actors, theater locations, etc.

In part three, the group queried the ontology, which included listing the instances of the class Actor, listing the name of all Thriller
movies and displaying their director, listing the name of all Crime Thriller movies, listing the name of actors older than 51 years,
and listing the movies played in theaters for a specific day and where and until when.

Part four involved manipulating the ontology using Jena, where the group developed several functionalities such as loading the ontology and
displaying all the persons (without using queries, without inference), loading the ontology and displaying all 
the persons (using a query, without inference), loading the ontology and displaying all the actors (without using queries, using inference),
developing a program that reads the name of a movie and displays its year, country, genres, and actors, displaying all persons that
are actors and directors using a rule that defines a new class ActorDirector, and specifying three different rules and implementing them in a Java program.

Overall, this project was an excellent opportunity for the group to develop their skills in Semantic Web programming
and work on a practical exercise that integrated several pieces that were covered in previous sessions.
