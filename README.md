# MVN Repo

Quick use of GitHub for hosting shared (public) Java code

## Retrieving Artifacts

Include the following repository in the `pom.xml`:

```xml
<repositories>
    <repository>
        <id>public-mvn-repo</id>
        <url>https://rawgit.com/Intilery/artifacts-public/master</url>
        <releases>
            <enabled>true</enabled>
        </releases>
        <snapshots>
            <enabled>true</enabled>
        </snapshots>
    </repository>
</repositories>
```
