This repository will contain all the java, spring, hibernate, mysql, elastic search, thread, related questions.


# Java
- ## OOPS
  - Solid principle of java(https://www.baeldung.com/solid-principles)
  - Object Cloning in Java
  - type of set in java
- ## Thread
  - Blocking queue
  - Producer and consumer approach
  - final syncronization variable or method can be possible?
- [Why Streaming?(FileUpload)](https://commons.apache.org/proper/commons-fileupload/streaming.html)
- Types of GC
- Allocating max head size for jar?
- Types of classloader and Bootstrap classloader?
- use of transient keyword
- HashMap is on which data structure?
- elliminated permGen memory block from java 8, why?
- optional with stream() can be applied or not?
- How to make class immutable?
- How many different ways to create objects in Java?
- [Why string is immutable class?](https://stackoverflow.com/questions/22397861/why-is-string-immutable-in-java)
- ## Java-8
  - [Wha is metaspace in java 8?](https://www.baeldung.com/java-permgen-metaspace)
  - [Supplier Interface in java](https://www.geeksforgeeks.org/supplier-interface-in-java-with-examples/)
  - [Predicate Interface in java](https://www.geeksforgeeks.org/java-8-predicate-with-examples/)
  - Parallel Stream with findFirst?
  - [Stateless and stateful operations of stream](https://www.oreilly.com/library/view/introduction-to-programming/9781788839129/50f54a6f-dd25-40bc-89d2-31b73d95b6b7.xhtml)
  - [How parallel stream works?](https://www.geeksforgeeks.org/what-is-java-parallel-streams/)
  - [What is major diff. between forEach and stream?](https://www.baeldung.com/java-collection-stream-foreach)
  


# Spring

- @Bean can be used at class level? 
  - https://docs.spring.io/spring-javaconfig/docs/1.0.0.M4/reference/html/ch02s02.html
  - https://www.baeldung.com/spring-bean-annotations 
- [What is difference between spring and spring boot?](https://www.baeldung.com/spring-vs-spring-boot)
- type of autowiring in spring
- [How to include one package to another package?](https://stackoverflow.com/questions/30425016/spring-boot-find-autowired-on-another-package)
- Use of @ComponentScan annotaion?
- [Can we use @component instead of @service in spring?](https://www.baeldung.com/spring-component-repository-service#:~:text=We%20can%20use%20%40Component%20across,Service%20and%20%40Repository%20in%20general.&text=%40Service%20and%20%40Repository%20are%20special%20cases%20of%20%40Component.)
- Why spingboot?
- How spring transaction management work?
- Best practice for writing naming convention of api URI.
- [What is a transitive Maven dependency?](https://stackoverflow.com/questions/41725810/what-is-a-transitive-maven-dependency)
- [Maven Dependency Scopes](https://www.baeldung.com/maven-dependency-scopes)
- [Types of IOC containers in Spring Framework](https://www.edureka.co/community/17155/types-of-ioc-containers-in-spring-framework)
- [What is servlet controller?](https://www.baeldung.com/spring-boot-servlet-containers#:~:text=Spring%20Boot%20allows%20developers%20to,Tomcat%2C%20Undertow%2C%20and%20Jetty.)
- [What is sping boot acuator](https://www.baeldung.com/spring-boot-actuators)

# Hibernate

http://hibernate.org/orm/documentation/5.4/

- [What Is a Second-Level Cache?](https://www.baeldung.com/hibernate-second-level-cache)
- Different annotations in hibernate?
- @OneToMany mapping?
- What is the use of @inheritance?
- How to use super class and sub class as indivisual entity?
- Where we can use @manyToMany mapping, explain we example?

# MySql

- self join of same table for username and manager name.
- What is the use of Composite key?
- MySql Tunning?
- [How to delete only duplicate/copy from employ table?](https://www.sqlshack.com/different-ways-to-sql-delete-duplicate-rows-from-a-sql-table/#:~:text=SQL%20delete%20duplicate%20Rows%20using%20Group%20By%20and%20having%20clause&text=The%20Group%20By%20clause%20groups,1%20in%20the%20Employee%20table.)
- [How to fetch first and last record from the table?](https://www.tutorialspoint.com/how-to-get-the-first-and-last-record-of-the-table-in-mysql#:~:text=To%20get%20the%20first%20and%20last%20record%2C%20use%20UNION.,number%20of%20records%20you%20want.)

# Elastic Search
https://www.elastic.co/guide/en/elasticsearch/reference/current/docs.html
- different types of queries
- less than and greater than
- How to fetch total record no. of a query?
- What is token filter(stopwords, tokenizer, etc)?
- What is analyser? How we can use this in ES?
- How to create mapping?
- What are different Http methods use in ES query?
- Instead of POST when we PUT some record/doc then what will happen?

# Design Pattern

- Why double check in Singleton?
- Singlton real world example.
- What is proxy class?
- How to create proxy design pattern?
- What is abstract design pattern?
- What is Command design pattern? Where we can use this?
- What are the different design pattern use in Spring framework?
- [How to prevent Singleton Pattern from Reflection, Serialization and Cloning?](https://www.geeksforgeeks.org/prevent-singleton-pattern-reflection-serialization-cloning/)
- [What is microservice design pattern?](https://www.edureka.co/blog/microservices-design-patterns)
