# Project

To Do Application
TECHNOLOGIES and TOOLS
- Spring Boot
- JPA (Hibernate) + MySQL
- LOMBOK
- IntelliJ
- Thymeleaf + Bootstrap CSS

## Steps Taken:
1. Create Spring Boot project in spring boot website (start.spring.io). Add Dependency
- Spring Web
- Spring Data JPA: Persist data in storage, make use of MySQL database
- MySQL driver: Interact with MySQL database
- LOMBOK: library that makes use of annotations that can help reduce boilet place code. Easy getters and setters example
- Thymeleaf:
  Check explore and youll see list of dependency added
  
2. Create a todo-app Schema in MySQL workbench
3. Add database configuration in application.properties. Set Spring data source url, username, password etc. -- define
4. Created InterafaceTaskRepository extending JpaRepository
5. Created a TaskController and a TaskService
6. Set @Service annotation in TaskService, created the getAllTask method
7. Set the @Controller for TaskController. Create method that return tasks, using @GetMapping annotations
8. Created tasks.html. I added thmymleaf. Set a for each loop that takes in the tasks in the todo-app db.
9. In my TaskControlelr I added createTask method with @PostMapping Rest API. I also made my createTask method in my TaskService.
10. Added deleteTask and toggleTask for both TaskController and TaskService
11. Use CSS Bootstrap for easier responsive web app

# Chat App
TECHNOLOGIES and TOOLS
BACKEND(Server-side)
Spring Boot
Spring WebSocket
Spring MEssaging (STOMP Protocol)
Thymleaf

FRONTEND(Client-Side)
Thymeleaf
JavaScript (ES6)
SockJS
Stomp.js
HTML/CC
BootStrap

DEVELOPEMENT AND INSFRASTRUCTUR TOOLS
MAVEN & IntelliJ

## Steps Taken:
1. Create Spring Boot project in spring boot website (start.spring.io). Add Dependency
- Spring Web
- Thymleaf
- WebSocket
- Lombok

2. Created a WebSocket class implementing WebSocketMessageBrokerConfigurer. Added 2 methods registerStompEnpoints and configureWebSocketTransport. Added @Configuration and @EnableWebSocketMessageBroker annotation
- Message broker kinda like a middleman to direct messages
- RegisterStompEndpoints: I defined the endpoint, security feautures and accesible to all user.
- ConfigureMessageBroker: I set the message broker and expect sent message

3. Added ChatMessage class and ChatController. ChatMessage is the model for the chat app. ChatController for Mapping. Create sendMessage and chat methods.
4. Added chat.html. Use CSS bootstrap for easier and interactive web app. 
5. Search and Added sockjs and stompjs in chat.html.
  


