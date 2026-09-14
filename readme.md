# OpenFeign Study

API simples para demonstrar o consumo declarativo de um servico REST externo com Spring Cloud OpenFeign.

A aplicacao consulta posts do JSONPlaceholder por meio de um cliente Feign e expoe o resultado em `GET /post`.

## Stack

Java 8, Spring Boot, Spring Web, Spring Cloud OpenFeign, Maven e Lombok.

## Executando

Execute `./mvnw spring-boot:run` ou, no Windows, `mvnw.cmd spring-boot:run`.

> Projeto educacional. Resiliencia, timeouts, observabilidade e testes de contrato sao melhorias recomendadas para producao.

## Autor

Desenvolvido por [Silas Melo](https://github.com/Silasmelo12).
