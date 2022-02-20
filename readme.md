# Maven Repository for CraftyServer
Read more about the project [here](https://github.com/CraftyServerMC/CraftyServer)
## Include this repository in your pom.xml
This is needed to include artifacts of CraftyServer.
```XML
<repositories>
  <repository>
    <id>CraftyServer-mvn-repo</id>
    <url>https://github.com/CraftyServerMC/maven/raw/mvn-repo/</url>
    <snapshots>
      <enabled>true</enabled>
      <updatePolicy>always</updatePolicy>
    </snapshots>
  </repository>
</repositories>
```
