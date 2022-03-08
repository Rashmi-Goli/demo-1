# Steps to run the application 

 ' ./mvnw spring boot:run'
OR
 './mvnw package' #to create the package (.jar file)
 
 'java -jar target/demo-1-0.0.1-SNAPSHOT.jar' #(to run the application)



## To access the application       
Run 'curl localhost:8080/greeting or curl localhost:8080/greeting?name=<name>'

or 

open a web browser and type http://localhost:8080/greeting or http://localhost:8080/greeting?name=<name>