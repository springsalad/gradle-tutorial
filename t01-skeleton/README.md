# Gradle Simple Skeleton for Maven User

## Truly Essential of Gradle for Maven User

 - the default of artifactId is the project name in setting.gradle you can set the project name like below:

```
rootProject.name = "something"
```
 - group signifies the groupId of the project/task that is being worked on.

```
com.example:my-project:0.1
----------- ---------- ---
     |         |        |
groupId  artifact  version

```

## Gradle Skeleton

```
├── gradle 
│   └── wrapper
│       ├── gradle-wrapper.jar
│       └── gradle-wrapper.properties
├── gradlew 
├── gradlew.bat 
├── settings.gradle 
└── 
├── build.gradle 
└── src
        ├── main
        │   └── java 
        │       └── demo
        │           └── App.java
        └── test
            └── java 
                └── demo
                    └── AppTest.java

```