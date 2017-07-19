

${HEADER}

#Dollar MapDB ${STATE_BETA}

MapDB wrapped up for use in Dollar.

To get started you'll need this repository:


```xml
    <repositories>
        <repository>
            <snapshots>
                <enabled>false</enabled>
            </snapshots>
            <id>bintray-sillelien-maven</id>
            <name>bintray</name>
            <url>http://dl.bintray.com/sillelien/maven</url>
        </repository>
    </repositories>
```  

and this dependency

```xml
        <dependency>
            <groupId>com.sillelien</groupId>
            <artifactId>dollar-mapdb</artifactId>
            <version>${RELEASE}</version>
        </dependency>
```

${BLURB}

${FOOTER}
