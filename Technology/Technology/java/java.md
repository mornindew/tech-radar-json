# Java

Java is one of the most commonly used languages in the world for enterprise software.  This is due to the ubiquitous nature of the language and the speed at which it can operate.  Typically Java is used in our microservices or our server side code that will handle requests coming from clients.   

# Overview Diagrams

If there are any overview diagrams needed to explain the technology then this is the place to put it.

# Standards - All coding standards that we use

## Style Guide
Java is a complex language and it is important that we all follow common style guides so that it is ledgeable for everyone who reads it.  We adhere to the Google Style guide for java

https://google.github.io/styleguide/javaguide.html

## Java Documentation
Java has a built in documentation tool called Javadocs.  It is important that everything is properly documented and javadocs are properly aggregated.  Follow this [link](https://www.oracle.com/technical-resources/articles/java/javadoc-tool.html) for java documentation and how to maintain proper docs.

Java docs will need to be stored in source code and built as part of the CI/CD pipeline.

## Patterns and Anti-Patterns

Java has a remarkable amount of patterns available to it.  The normal challenge with Java is allowing it's flexibility create confusion.

**High Level Patterns**

|     Name                  |Pattern                        |Anti-Pattern                 |Rationale   |
|---------------------------|-------------------------------|-----------------------------|------------|
|Composition vs Inheritance |Prefer composition over inheritance            |Unnecessary complicated inheritance structures            |This will complicate your code            |
|Singleness of purpose      |Every method or function should do one and one thing only            |Having complicated methods and functions that perform multiple tasks            |            |
|Code Separation                     |Use package naming to separate your logic |-- is en-dash, --- is em-dash|            |




# Training Materials

Any training materials that are needed with links.  The point is not to write training materials.  It is to send people to places to learn.

## Sample Repos

This is any sample repos for the technology

