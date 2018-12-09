# spring-boot-mvc
It is playground for spring mvc
1. Default configuration can be overriden in `application.properties` file

2. Configuration required to package application as war file
    
    a. pom.xml changes
    
        1. change packaging from jar to war
            <packaging>war</packaging>
            
        2. Add below line in pom.xml file
        
                    <dependency>
                        <groupId>org.springframework.boot</groupId>
                        <artifactId>spring-boot-starter-tomcat</artifactId>
                        <version>2.0.4.RELEASE</version>
                        <scope>provided</scope>
                    </dependency>
            