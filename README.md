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
```

# Properties

|    name    |     discription      |                 defaultValue                  |
| :--------: | :------------------: | :-------------------------------------------: |
|  groupId   |   Project GroupId    |                       -                       |
| artifactId |  Project ArtifactId  |                       -                       |
|  version   |   Project version    |                 1.0-SNAPSHOT                  |
|  package   | Project package FQCN | `${groupId}.${artifactId.replaceAll("-", ".")}` |
