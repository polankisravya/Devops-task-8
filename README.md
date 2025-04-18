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

### Jenkins Job Setup

1. Open Jenkins Dashboard
2. Create a new Freestyle Job
3. Connect your GitHub repository (provide the repo URL)
4. Add build step: `mvn clean install`
5. Save and Build the job


## Output
- Console Output shows `BUILD SUCCESS`

## Screenshot
(![image](https://github.com/user-attachments/assets/66a1299c-ed33-405f-96f4-fc676336ea44)
)

---
