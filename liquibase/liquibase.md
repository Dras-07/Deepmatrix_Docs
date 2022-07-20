<h1>Quarkus_Liquibase</h1>

Installation

1) Download Liquibase 
2) Change environment variable

Command to Generate changelogs
```
liquibase --driver=org.postgresql.Driver  --classpath=C:\deepmatrix\liquibase\project-1\postgresql-42.2.25.jre7.jar   --changeLogFile=C:\deepmatrix\liquibase\project-1\changelog.xml --url=jdbc:postgresql://68.183.87.6:5432/drishti-dev  --username=dmadmin  --password=Postgres@dm2022 generateChangeLog 
```



<a><p>https://capgemini.github.io/development/Quarkus-meets-Liquibase/</p></a>
<a><p>https://quarkus.io/guides/liquibase </p></a>

<ul>
<li>Create 2 classes Migration resource and Migration Service</li>
<li>Change application properties and configure changelog.xml file path</li>
<li>Add the liquibase dependency in pom.xml</li>
</ul>


