# Steps to run the application 

 ' ./mvnw spring boot:run'
OR
 './mvnw package' #to create the package (.jar file)
 
 'java -jar target/demo-1-0.0.1-SNAPSHOT.jar' #(to run the application)



## To access the application          
Run 'curl localhost:8080/greeting or curl localhost:8080/greeting?name=<name>'

or 

open a web browser and type http://localhost:8080/greeting or http://localhost:8080/greeting?name=<name>

## creating a docker image.

1. new file Dockerfile -> FROM <image>
                       ARG <PATH TO JAR FILE>
                       COPY
                       ENTRYPOINT <PATH>

2. docker build  <image name> .
3. docker push <docker registry>


## running docker image on fargate service
1. create a user on IAM with ECS full access policy. 
2. create a policy with ECR full access for us-east-1 region
3. attach the new policy to the user
4. create a docker image 
5. login to aws using aws configure command and giving the new user credentials
6. 


