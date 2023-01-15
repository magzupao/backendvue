Desarrollo
https://github.com/in28minutes/spring-boot-vuejs-fullstack-examples
1. Creamos la estrcutura del proyecto usando la herramienta online spring: https://start.spring.io/

Group:          com.example
Artifact:       demo
Name:           demo
Description:    Demo project for Spring Boot
Package name:   com.example.demo

2. Creamos los recursos:
model: CourseService.java
service: CourseService.java
controller: CourseController.java

3. Usamos un cliente http
Post: http://localhost:8080/instructors/magz/courses
mensaje json: {"id":"5","username":"marco guado","description":"prueba"}

Get: http://localhost:8080/instructors/magz/courses

