Summary
The project is a Maven archetype for Spring Boot web application 

Java 1.8+
Maven 3.2+
Spring boot 2.1.0.RELEASE+

To create archetype use below command.This is not required to create sample project but to required to create archetype template

mvn archetype:generate -B -DarchetypeArtifactId=maven-archetype-archetype  
-DgroupId=com.subhajit.archetype 
-DartifactId=myapp-archetype 
-Dversion=1.0.0-SNAPSHOT


Installation
To install the archetype in your local repository execute following commands:


$ git clone https://github.com/subhajitgoswami/myapp-archetype.git
$ cd myapp-archtype
$ mvn clean install

Create a project
$ mvn archetype:generate \
     -DarchetypeCatalog=local \
     -DarchetypeArtifactId=myapp-archetype \
     -DarchetypeGroupId=com.subhajit.archetype \
     -DarchetypeVersion=1.0.0-SNAPSHOT
     
Sample app generated from that archetype
https://github.com/subhajitgoswami/sampleproject.git
