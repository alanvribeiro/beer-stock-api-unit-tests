# Testes unitários em API Rest de Gerenciamento de Estoque de Cervejas

Este projeto consiste na validação de uma API Rest de Gerenciamento de Estoque de Cervejas através de testes unitários com JUnit, Mockito e Hamcrest, utilizando a prática TDD.

## Stack utilizada

* Java 14
* Spring Boot
* Maven
* H2 Database
* Lombok
* MapStruct
* Swagger
* JUnit, Mockito e Hamcrest
* IntelliJ IDEA

## Informações adicionais

Para executar o projeto no terminal

```
mvn spring-boot:run 
```

Para executar a suíte de testes

```
mvn clean test
```

Para visualizar a execução do projeto

```
http://localhost:8080/api/v1/beers
```

Para acessar a documentação da API

```
http://localhost:8080/swagger-ui.html
```
