# labs_Java

### TASK FOR LAB 8:
 - Write code for Lab 2(UML diagram)
 - Use java code convention
 - CLasses must be distributed in packages
 - Work with console must be minimal
 - Code must contain only that classes that are described in the diagram
 - Sorting must use java built-in methods
 - Sorting must be implemented in separate method
 - No static methods/attributes are allowed (the only exception is a main method)
 - You must use Enums
 - Code must be in a separate branch with PR
 - Comparison must be implemented using lambdas
 - Instead of getters/setters you should use `@Data` annotation from lombok
 - Use maven and Jococo(in build section), FindBugs, PMD, CheckStyle plugins
 - Run `mvn site` and fix errors reported by checkstyle, pmd and findbugs
 
### TASK FOR LAB 9:

+ Create REST service and implement CRUD operations on object from 8-th lab.
+ GET operation should use id
+ GET operation without id should return list of all objects
+ To implement REST service base class from 8-th lab should be expanded with id field of type int
+ Code should be checked with findbugs, checkstyle and pmd plugins
+ Code should be in a different pull request than lab8
+ Controller and RestApplication should be in a different packages
+ Objects should be stored in a Map


### TASK FOR 10 LAB:
Implement saving of one of the classes from 8-th lab in a table in a database using `spring.boot` and `spring.data`
 - 9-th lab code should be changed in such way, that permits saving/reading data to/from database
 - Code should comply with code convention
 - Code should be checked with findbugs, pmd and checkstyle plugins
 - A separate pull request should be created
 - Code must contain separate `*Controller`, `*Service` and `*Repository` classes
 - Configuration of database accessing should be done through properties file



### TO RUN:
 - Clone/download LabNo8 branch
 - If you`re using IntelliJi IDEA: push 'RUN' button. 
 - Else:
 - Open cmd and go to the into repo folder
 - Run `mvn compile`
 - Go into `target/classes` and run `java ua/lviv/iot/shop/App` 
 
 ### USEFUL COMMANDS:
- mvn checkstyle:check
- mvn findbugs:gui
- mvn pmd:pmd
