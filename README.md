# Java-Best-Practices-outline-
  not a complete list of best practices

# Creating Objects
  - Consider static factory methods instead of constructors
  - Consider a builder when faced with many constructor parameters
  - Prefer try-with-resources to try-finally
 
# Methods Common to All Objects
  - Always override hashCode when you override equals
  - Always override toString
  - Consider implementing Comparable (+ how is it done since Java 8)
  
# Classes and Interfaces
  - Prefer interfaces to abstract classes

# General Programming
  - Prefer for-each loops to traditional for loops
  - Avoid float and double if exact answers are required
  - Prefer primitive types to boxed primitives
  - Avoid strings where other types are more appropriate
  
  
# Some other topics
  - SonarCube - Quality Gates
  - Lazy init
  - Reflection
  - Spagetti code
  - Types of testing
  
# How not to do
  - examples of a production system Java code
