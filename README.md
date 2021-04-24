#Desenvolvimento de testes unitários para validar uma API REST de gerenciamento de estoque de cervejas

Este projeto consiste na validação uma API REST de gerenciamento de estoque de cervejas através de testes unitários com JUnit, Mockito e Hamcrest, utilizando a prática TDD.

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

## Informações adicinais

Para executar o projeto no terminal:

```shell script
mvn spring-boot:run 
```

Para executar a suíte de testes:

```shell script
mvn clean test
```

Após executar o comando acima, basta abrir o seguinte endereço e visualizar a execução do projeto:

```
http://localhost:8080/api/v1/beers
```
