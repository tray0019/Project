# Project

To Do Application
TECHNOLOGIES and TOOLS
- Spring Boot
- JPA (Hibernate) + MySQL
- LOMBOK
- IntelliJ
- Thymeleaf + Bootstrap CSS

Steps Taken:
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
