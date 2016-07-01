andsrifcs2maven
===============

This is a maven pom to install ANDS-RIFCS-API into maven repository.

1. Download the ANDS-RIFCS-API repository 
```
 git clone https://github.com/au-research/ANDS-RIFCS-API
```
2.  cd into the ANDS-RIFCS-API project directory and build the project
```
ant build_jar
```
3.   cd into this project directory and, noting the relative location of the ANDS-RIFCS-API jar artifact, overwrite the pom property: 'ands.jar.directory'
before running maven
```
mvn install
```