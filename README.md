# dropwizard-maven-archetype
Maven archetype:generate dropwizard

```bash
mkdir -p /tmp/app ; cd /tmp/app
mvn -N io.takari:maven:wrapper -Dmaven=3.5.4
./mvnw archetype:generate -DarchetypeGroupId=io.dropwizard.archetypes \
                          -DarchetypeVersion=1.1.0 -DarchetypeArtifactId=java-simple \
                          -DgroupId=com.github.daggerok \
                          -Dversion=1.0.0-SNAPSHOT \
                          -DartifactId=app \
                          -Dname=app
# output / confirm:
Confirm properties configuration:
groupId: com.github.daggerok
artifactId: app
version: 1.0.0-SNAPSHOT
package: com.github.daggerok
description: null
name: app
shaded: true
 Y: : y
```
