# Usage

## Clone This Repository

`git clone https://github.com/gn5r/gn5rapl-archetype.git`

`mvn install`

## Create Java Project Using This Archetype

```
mvn archetype:generate -DarchetypeGroupId=com.github.gn5r \
-DarchetypeArtifactId=gn5rapl-archetype \
-DarchetypeVersion=1.0.0 \
-DgroupId=your project groupId \
-DartifactId=your project artifactId \
-Dversion=your project version \
-Dname=main class prefix
```

# Properties

|        name         |       description        |                  defaultValue                   |
| :-----------------: | :----------------------: | :---------------------------------------------: |
|       groupId       |     Project GroupId      |                        -                        |
|     artifactId      |    Project ArtifactId    |                        -                        |
|       version       |     Project version      |                  1.0-SNAPSHOT                   |
|      packaging      |    Project packaging     |                       war                       |
|       package       |   Project package FQCN   | `${groupId}.${artifactId.replaceAll("-", ".")}` |
|        name         |     MainClassPrefex      |                        -                        |
|  gn5r-boot-version  | gn5r-boot-starte version |                 1.0.0-SNAPSHOT                  |
| spring-boot-version |   spring boot version    |                     2.5.14                      |
