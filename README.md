
#### Possivel problema quando for ultilizar o template, relacionado a dependência de CDI⚠️

##### Caso estiver usando servidor como  [Apache-Tomcat](https://mvnrepository.com/artifact/org.jboss.weld.servlet/weld-servlet) essa é a dependencia correta!(Recomendado)


``` <!-- https://mvnrepository.com/artifact/org.jboss.weld.servlet/weld-servlet-core -->
<dependency>
    <groupId>org.jboss.weld.servlet</groupId>
    <artifactId>weld-servlet-core</artifactId>
    <version>3.1.7.Final</version>
</dependency>
````

#### No caso de usar outro servidor, como Wildfly ou JBoss (pode haver erros, pois não utilizei esse servidor

``` <!-- https://mvnrepository.com/artifact/javax.enterprise/cdi-api -->
<dependency>
    <groupId>javax.enterprise</groupId>
    <artifactId>cdi-api</artifactId>
    <version>2.0</version>
    <scope>provided</scope>
</dependency>
````
