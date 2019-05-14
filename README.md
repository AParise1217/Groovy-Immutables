# Archetypes
Various Domain Archetype Patterns implemented in Groovy.


# Sources
Much of these models are based on those presented in "Enterprise 
    Patterns and MDA" by Jim Arlow and Ila Neustadt. I highly recommend 
    picking up a copy of this book to get a better understanding on 
    model driven architecture.

# Release Steps

Make sure the "release-sign-artifacts" and "ossrh" 
    Maven profiles are active.

1) `mvn clean`
2) `mvn release:prepare`
3) `mvn release:perform`


