mvn archetype:generate -DarchetypeArtifactId=jersey-quickstart-webapp -DarchetypeGroupId=org.glassfish.jersey.archetypes -DinteractiveMode=false -DgroupId=com.demo -DartifactId=rest-services -Dpackage=com.demo -DarchetypeVersion=2.31


Project build and management configuration is described in the pom.xml located in the project root directory.
Project sources are located under src/main/java.
Project resources are located under src/main/resources.
Project web application files are located under src/main/webapp.


Run Maven application:

mvn clean package