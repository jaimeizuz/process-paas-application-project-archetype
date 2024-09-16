# Steps
1. Install the archetype with ``mvn clean install``
2. Create a sample project based on the maven archetype with: 

	``mvn archetype:generate "-DarchetypeGroupId=com.santander.processes" "-DarchetypeArtifactId=process-paas-application-project-archetype" "-DarchetypeVersion=1.0.0-SNAPSHOT" \
		"-DgroupId=loans" "-DartifactId=loan-process" "-DinteractiveMode=false"``

