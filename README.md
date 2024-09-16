# Purpose
Archetype will be used to generate tempate projects to work with dmn.

# Building
mvn archetype:generate "-DarchetypeGroupId=org.sakila.videostore" "-DarchetypeArtifactId=sakila-videostore-process-project-archetype" "-DarchetypeVersion=1.0.0-SNAPSHOT" "-DgroupId=loans" "-DartifactId=loan-process" "-DinteractiveMode=false"

# Build and Test
mvn install

