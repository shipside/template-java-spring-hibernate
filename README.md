
# Spring MVC and Hibernate template application

This is a template for a web application that uses Spring MVC and Hibernate. The sample code is a simple CRUD page that manipulates records for a single model object.

##Support eclipse project files (JavaEE for Web Luna Realease 4.4.0)


## Running the application locally


### Eclipse
Create project file and open in Eclipse, run it in Tomcat server
    cp .project.basic .project
    
    
### Maven
First build with:

    $mvn clean install

Then run it with: (uncommit <artifactId>webapp-runner</artifactId> in pom.xml)

    $java -jar target/dependency/webapp-runner.jar target/*.war
    
    
    

