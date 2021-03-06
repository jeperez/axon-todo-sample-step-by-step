A Todo List Application with AxonFramework, step by step
========

Introduction
---------

This is a sample application designed with the following patterns:

- [Domain Driven Design](http://domainlanguage.com/ddd/)
- [CQRS](http://martinfowler.com/bliki/CQRS.html)
- [Event Sourcing](http://martinfowler.com/eaaDev/EventSourcing.html)

To achieve this, it will be made use of the frameworks:

- [Axon Framework](http://www.axonframework.org/)
- [Xtend](http://eclipse.org/xtend/)
- [Maven Polyglot](https://github.com/takari/maven-polyglot)
- [Hibernate](http://hibernate.org/)/EclipseLink
- [Spring](http://projects.spring.io/spring-framework/)
- [Vert.x](http://vertx.io/)
- ...

The application will be created step by step. Each step will be illustrated by a Maven project. The first steps provide only a runner displaying messages on a console.

Eclipse is used to edit the projects.

Step by step
-------

In fact, the first steps deal with a Hello World application, to stick to the most commun minimalistic model.

#### [Step 0](step0) - Helloworld ####

A bare bone [Maven](https://maven.apache.org/) project to print a simple "Hello World!" on the console, using the File System to store the events.

#### [Step 1](step1) - Helloworld again ####

Refactoring of the Maven pom and the runner.

#### [Step 2](step2) - Helloworld with [Xtend](http://eclipse.org/xtend/) ####

Refactoring with [Xtend](http://eclipse.org/xtend/).

#### [Step 3](step3) - Helloworld with [Polyglot for Maven](https://github.com/takari/maven-polyglot) ####

Use [Polyglot for Maven](https://github.com/takari/maven-polyglot) with [Groovy](http://groovy-lang.org/)

#### [Step 4](step4) - Helloworld with JPA persistence ####

Use JPA for persistence. Require Spring.  

Building
-------

From each Maven project:

        mvn package


Running
-------

See README.md file of each Maven project.

References
---------

[Axon 2 QuickStart Guide](http://www.axonframework.org/axon-2-quickstart-guide/)

[avthart/spring-boot-axon-sample](https://github.com/avthart/spring-boot-axon-sample)  
Sample application using Spring Boot, Axon, ElasticSearch, AngularJS and Websockets


[Basic Axon Framework sample using vert.x and angular.js](http://blog.trifork.com/2012/11/27/basic-axon-framework-sample-using-vert-x-and-angular-js/)

Documentation
----------

[Domain Driven Design : des armes pour affronter la complexité](http://blog.octo.com/domain-driven-design-des-armes-pour-affronter-la-complexite/)

[A la rencontre d’une architecture méconnue : CQRS](http://blog.clever-age.com/fr/2012/01/05/a-la-rencontre-d-une-architecture-meconnue-cqrs/)

CQRS, l’architecture aux deux visages :

- [1ère partie](http://blog.octo.com/cqrs-larchitecture-aux-deux-visages-partie-1/)
- [2e partie](http://blog.octo.com/cqrs-larchitecture-aux-deux-visages-partie2/)

[Event Sourcing vs Command Sourcing](http://thinkbeforecoding.com/post/2013/07/28/Event-Sourcing-vs-Command-Sourcing)


Licenses
--------

[Apache 2 license](http://www.apache.org/licenses/LICENSE-2.0)
