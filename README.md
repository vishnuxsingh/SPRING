# SPRING
Spring Boot Notes 
Spring FrameWork --->
LECTURE 1 :  Spring Boot & Spring Framework OverView
Client-server architecture is a way of designing software where two main parts work together:
Client → The device/app that the user interacts with.
Server → A computer/system that provides data or services to the client.
Simple example
When you open Instagram:
📱 Client: Your Instagram app sends a request: “Show me my feed.”
🌐 Server: Instagram's server receives the request.
🗄️ Database: The server gets your posts/data from its database.
🌐 Server: Sends the data back to your phone.
📱 Client: The app displays the feed.
So, basically:
Client → Request → Server → Response → Client
Real-world analogy
Think of a restaurant:
You = Client
Waiter = Network/API
Kitchen = Server
Storage/ingredients = Database
You ask for food → waiter takes the request → kitchen prepares it → waiter brings it back.
Why use client-server architecture?
It allows:
Many clients to use the same server
Centralized data storage
Easier security and data management
Servers to handle heavy processing
Apps/websites to communicate with databases
In one sentence: Client-server architecture means the client asks for something, and the server processes the request and sends back the result.

HTTP -> Hyper Text Transfer Protocol 
this is protocol 
HTTP is the communication protocol between the client and server.
Client-Server = Who communicates?
HTTP = How they communicate?
BODY OF REQUEST / RESPONSE ->
REQUEST-> METHOD NAME -> URL/PATH -> HEADERS-> BODY
RESPONSE -> Status Code -> HEADERS -> BODY


servlet & servlet Container ->
tomcat - >

spring - > 
Spring Boot->>
spring MVC -> 
spring Data -> for connection with db
spring -> AOP ->
Spring security - >
Spring AI->
all above comes in spring core 
<img width="1110" height="595" alt="image" src="https://github.com/user-attachments/assets/b6dfd6fb-15d9-4f96-83c2-1dfe9b0e4567" />

                    JAVA WEB APPLICATION
                           │
                    Servlet Container
                           │
                     Tomcat Server
                           │
                    Spring Framework
          ┌────────────────┼─────────────────┐
          ↓                ↓                 ↓
     Spring MVC       Spring AOP       Spring Security
          ↓
     Spring Boot
          ↓
     Spring Data
          ↓
       Database

                 Spring AI
                    ↓
               AI Models/APIs

Spring Security → Security
Spring AOP      → Cross-cutting concerns
Spring AI       → AI integration
Spring Boot     → Makes the whole Spring application easier to build/run
Spring Core     → IoC, DI, Beans, Container


Master Apache Maven in one video | POM, Dependencies & Lifecycle | Spring Boot Full Course #3
JAR FILES -> JAVA Archives -> this is type of package which can have multiple .class files, Resources , Folders/Packages etc 
a centralized storage.
2. To use external Libraries (my-sql-connector.jar)
MAVEN ->> it is kind of project management tool.
   1. mantains folder structure
   2. compile code
   3. creates jar file
   4. dependencies download
pom.xml-> project object model









Build Your First Spring Boot Application | REST API | Spring Boot Full Course #2
REVERSE PROXY->mapping of ports 
DNS-> domain naming system 
start.spring.io


tags in POM.xml ->>
https://mvnrepository.com/ -> For getting any deoendencies.
super pom -> parent of allpom
effective pom -> which our project uses
maven life cycle ->
1. clean life cycle-> clean
2. default lifecycle->validate,compile,test,package,verify,install,deploy
3. sitelifecycle ->site

   mvn clean install
   for cleab and install depenencues
   
