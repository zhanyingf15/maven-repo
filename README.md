

## usage

```xml
<repositories>
    <repository>
      <id>wjj-maven-repo</id>
      <url>https://raw.github.com/zhanyingf15/maven-repo/master</url>
    </repository>
</repositories>
```

if use the mirror fragment in settings.xml file,ensuer that the wjj-maven-repo repository is excepted  in the mirrorOf tag.

```xml
<mirror>
      <id>nexus</id>
      <mirrorOf>*,!wjj-maven-repo</mirrorOf> 
      <url>http://maven.aliyun.com/nexus/content/groups/public/</url>
</mirror>
```



