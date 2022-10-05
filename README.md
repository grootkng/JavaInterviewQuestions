<h1 align="center">A Java and Spring source of interview questions</h1>

<h2 align="center">Questions</h2>

### Java
1. What is the difference between string buffer and string builder?  
```
  String buffer and StringBuilder both are mutable classes which can be used to do operation on 
  string objects such as reverse of string, concating string and etc. We can modify string without 
  creating a new object of the string. 
  A string buffer is thread-safe whereas string builder is not thread-safe
```

2. Where do the normal variables, objects store in memory?
```
  Stack in java is a section of memory which contains methods, local variables, and reference variables
  And in Java, all objects are dynamically allocated on Heap
```

3. Is java 100% OOP language? Explain it.
```
  No, because it uses primitive datatypes like int, float, char, double. 
  A pure OOP language can use nothing, but objects i.e everything must be a class. 
```

4. Why do we have different memories like heap memory, stack memory, dynamic memory?

5. Why is string immutable? In which memory does it store data?
```
The String is immutable in Java because of the security, synchronization and concurrency, 
caching, and class loading. The reason of making string final is to destroy the 
immutability and to not allow others to extend it. The String objects are cached in 
the String pool, and it makes the String immutable.
```

6. How is the data stored in HashMap?
7. What is the difference between HashMap and HashTable?
8. What is the difference between HashSet and TreeSet?
9. Can we extend a class to interface?
10. How will you clone the object in java? Which interface is used? Which method is used for cloning?
12. What is the use of java streams? Why should we use streams?
13. Why main function has a public static void? What does it mean?
14. What is the difference between errors and exceptions?
15. What is the difference between static and non-static context?
16. Can you name some synchronized collections?
17. What is the difference between the sleep and wait for method in a thread? Which method is invoked once a thread is waiting?

### Spring
1. What is the difference between @Controller and @RestController?
```
  The main difference between the @restcontroller and the @controller is 
  that the @restcontroller combination of the @controller and @ResponseBody annotation. 
  RestController: RestController is used for making restful web services with the 
  help of the @RestController annotation
```

2. What is the @Transaction in Spring?
3. What is the use of @ControllerAdvice in Spring?
4. What is the difference between spring MVC and Spring boot?
5. What is the use of @SpringBootApplication?
6. What is Springboot Actuator?
7. How do you communicate between services in two different boot services?
8. Can we have two @ControllerAdvice in one project?
9. What are the propagations and isolations levels do you know in Spring?
10. Explain the difference between Spring Boot and Spring framework
11. What is @Qualifier used for in Spring?

### Hibernate
1.  What is the use of @Lazy and @Eager in hibernate?
2. What are the design patterns used in hibernate framework?
3. How to enable the second-level cache?

### Database | SQL
1. What is View in POSTGRESQL | Materialized View in POSTGRESQL | Refresh Materialized view | SQL Views?
```
  In a database, a view is the result set of a stored query on the data, which the 
  database users can query just as they would in a persistent database collection object. 
  This pre-established query command is kept in the database dictionary
```

2. What is the difference between vertical partitioning vs horizontal partitioning in database?
3. Hany types of indexes are there? What are they? When to use what? Is indexing DBA Job or Developer job?
4. What is the best way to modify the existing composite key in SQL?
5. Consider if any update is taking time. What are the consequences that are causing performance issues? How can you avoid it?
