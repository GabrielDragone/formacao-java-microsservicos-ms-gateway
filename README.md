# Formação Aprofunde em Java com arquitetura de Microsserviços, Spring e RabbitMQ:
Curso alura: https://cursos.alura.com.br/formacao-java-microsservicos

Projeto e anotações referentes à formação "Aprofunde em Java com arquitetura de Microsserviços, Spring e RabbitMQ".

Microsserviço de Gateway, funcionária junto com o de Pagamentos, Pedidos e MS Eureka Server.

Ler as anotações abaixo para mais detalhes:
https://github.com/GabrielDragone/formacao-java-microsservicos-ms-pagamentos

---

## Para rodar a aplicação:
* Rodar o ms-pagamentos primeiro e criar o banco manualmente no postgres.
* Abrir o Docker Desktop.
* Rodar o comando para subir o container postgres: docker-compose up.
* Rodar a aplicação através da [GatewayApplication.java](src%2Fmain%2Fjava%2Fbr%2Fcom%2Fgabrieldragone%2Fgateway%2FGatewayApplication.java).
* Acessar o swagger pra fazer as requisições: http://localhost:{{portaDefinidaNoEureka}}/swagger-ui/index.html

---