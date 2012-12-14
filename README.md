aquery-maven-repository
=======================

A simple maven repo to get aQuery.

Add the following to your pom file:

    <repositories>
      ...
      <repository>
        <id>aquery-maven-repository</id>
        <url>https://raw.github.com/4impact/aquery-maven-repository/master/releases/</url>
      </repository>
      ...
    </repositories>
    
    
    <dependencies>
        ...
        <dependency>
             <groupId>com.androidquery</groupId>
             <artifactId>androidquery</artifactId>
            <version>0.24.3</version>
         </dependency>
        ...
    </dependencies>
    
    
