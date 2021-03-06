# Java-Best-Practices-outline-
  not a complete list of best practices

# Creating Objects
  - Consider static factory methods instead of constructors
    
  - Consider a builder when faced with many constructor parameters 
    - Effective Java / VehicleBuilder Example
  - Prefer try-with-resources to try-finally
    - Effective Java / TryWithResourceMain.java
    - Effective Java / ImprovedExceptionHandling.java
 
# Methods Common to All Objects
  - Always override hashCode when you override equals
    - Effective Java / HashCodeEqualsPersonMain.java
  - Always override toString
    - Effective Java / HashCodeEqualsPersonMain.java 
  - Consider implementing Comparable (+ how is it done since Java 8)
    - Effective Java / Pojos / Person.java + PersonComparableMain.java

# General Programming
  - Prefer for-each loops to traditional for loops
    - Effective Java / TraditionalForLoop.java
  - Avoid float and double if exact answers are required
    - Effective Java / BigDecimalOverFloat.java
  - Prefer primitive types to boxed primitives
    - Effective Java / LongInForLoopPerformance.java
  - Avoid strings where other types are more appropriate
    - Effective Java / StringConcatenationAndPerformance.java
  
  
# Some other topics
  - SonarCube - Quality Gates
    - lightBSM : http://localhost:9000/dashboard?id=lightbsm20191110
  - Lazy init
  - Reflection
  - Spagetti code
  - Types of testing
  - Streams
  - Lambda Expressions
  
# How not to do
  - examples of a production system Java code
