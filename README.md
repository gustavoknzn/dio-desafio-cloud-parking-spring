# Cloud Parking

- [Ferramentas Usadas](#ferramentas-usadas)
- [Como executar](#como-executar)

## Ferramentas Usadas

- IDE de Desenvolvimento: [IntelliJ IDEA Community Edition (2022.1.4) Openjdk "11.0.15"](https://www.jetbrains.com/pt-br/idea/download)
- Gerenciador de Dependências: [Maven 4.0.0](https://maven.apache.org/)
- Framework para desenvolvimento da API: [Spring Boot 2.4.0](https://spring.io/projects/spring-boot)
- Servidor de Aplicação: [Apache Tomcat 9.0](http://tomcat.apache.org/)
- Testes da API RESTful: [Postman](https://www.getpostman.com/) 
- Banco de dados: [PostgreSQL](https://www.h2database.com/html/main.html](https://www.postgresql.org/)
	
	*Aplicação rodando
	URL Base: http://localhost:8080/h2-console/

- Documentação API com Swagger [Guia de documentação básica da API](http://localhost:8080/swagger-ui.html#/)

	*Aplicação rodando
	URL Base: http://localhost:8080/swagger-ui.html#/
  
  ## Como Executar

- Instalar a IDE [IntelliJ IDEA Community Edition (2022.1.4) Openjdk "11.0.15"](https://www.eclipse.org/)
- Importar projeto
- Aguardar o download das depedências
- Executar os comandos abaixo
 ```sh
 docker run --name parking-db -p 5432:5432 -e POSTGRES_DB=parking -e POSTGRES_USER=admin -e POSTGRES_PASSWORD=123 -d postgres:10-alpine
 docker start parking-db
 ```
- Após a aplicação subir acessar acessar o [Swagger](http://localhost:8080/swagger-ui.html#/)


## [Meu LinkedIn](https://www.linkedin.com/in/gustavo-konzen-70373b189/)

