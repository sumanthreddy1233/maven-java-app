# maven-java-app
This is a sample maven app 
## About mvn archetype:generate
### Guide to Creating Archetypes
* Creating an archetype is a pretty straight forward process. An archetype is a very simple artifact, that contains the project prototype you wish to create.
* An archetype is made up of:
* an archetype descriptor (archetype-metadata.xml in directory: src/main/resources/META-INF/maven/). 
* It lists all the files that will be contained in the archetype and categorizes them so they can be processed correctly by the archetype generation mechanism.
* the prototype files that are copied by the archetype plugin (directory: src/main/resources/archetype-resources/)
* the prototype pom (pom.xml in: src/main/resources/archetype-resources)
* a pom for the archetype (pom.xml in the archetype's root directory).

## Source for the above mentioned guide: https://maven.apache.org/guides/mini/guide-creating-archetypes.html

