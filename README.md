# Task 8 - Java Maven Build with Jenkins

## Overview
This task demonstrates how to configure a simple Java Maven project and build it using a Jenkins Freestyle job.

## Project Structure
```
hello-java-maven/
├── pom.xml
└── src/
    └── main/
        └── java/
            └── HelloWorld.java
```

## Jenkins Setup
- **Maven Version:** 3.8.6
- **Java Version:** 1.8
- **Jenkins Job Type:** Freestyle
- **Build Goal:** `clean package`

## Output
- Console Output shows `BUILD SUCCESS`

## Screenshot
(Add a screenshot here showing successful Jenkins build)

---

## Questions
1. **What is Jenkins?**
   Jenkins is an open-source automation server for building, testing, and deploying software.

2. **What is Maven used for?**
   Maven is a build automation tool for Java projects, handling dependencies, compiling code, and packaging it.

3. **How does Jenkins use Maven?**
   Jenkins uses Maven to compile Java code, resolve dependencies, and build the project through configured jobs.
