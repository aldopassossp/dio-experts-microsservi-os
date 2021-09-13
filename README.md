# **Construindo um projeto com arquitetura baseada em microsserviços utilizando Spring Cloud**

### OBJETIVO

Aprender como funciona uma arquitetura de micro serviços, criando um Gateway para controlar o fluxo de dados e requisições de uma aplicação fazendo a interligação de API's com Servers de configuração.

### TECNOLOGIAS

- Java 11
- Spring Boot 2.5.4
- Spring Boot Actuator
- Spring Cloud
- Spring Cloud Netflix
- ElasticSearch 7.14
- Redis 6.2.5
- Docker

### INSTALAÇÃO LOCAL

- Faça um git clone deste Repositório

- Suba os servidores no docker que estão no arquivo docker-compose.yml  através do comando:

  ```
  docker -compose up
  ```

- Primeiramente importe os projetos como módulos em sua IDE, depois rode primeiro os projetos: config-server e service-discovery. Então já pode rodar os demais projetos

### BANCO DE DADOS

Foram utilizadas duas soluções NO-SQL neste projeto, sendo elas o ElasticSearch e o Redis.

### BIBLIOTECAS DO PROJETO

Neste projeto foram alteradas as versões das dependências para as mais atuais no momento de publicação deste projeto. Algumas códigos de configurações tiveram que ser completamente remodeladas para poder funcionar nas versões atuais.

Caso queira dar uma olhada no projeto original: https://github.com/oswaldoneto/dio-experts

