# WSO2 Handler Maven Archetype <!-- omit in toc -->

Maven Archetype for WSO2 Handlers. Use the following maven archetype to generate maven projects to implement WSO2 related handlers for WSO2 API Manager and WSO2 EI Services.

```xml
<dependency>
    <groupId>com.athiththan.wso2</groupId>
    <artifactId>wso2-handlers</artifactId>
    <version>1.0.0</version>
</dependency>
```

## Usage

```shell
mvn archetype:generate  -DarchetypeGroupId=com.athiththan.wso2  \
                        -DarchetypeArtifactId=wso2-handlers     \
                        -DarchetypeVersion=1.0.0                \
                        -DgroupId=<Group ID>                    \
                        -DartifactId=<Artifact ID>
```
