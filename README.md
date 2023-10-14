<h1 align="center">TodoList API</h1>

Aplicação construída durante o primeiro evento de Java da [Rocketseat](https://rocketseat.com.br), baseia-se em uma API de gerenciamento de tasks registradas por usuários construído com
[Spring-Boot](https://spring.io/projects/spring-boot) e também ela está com o deploy feito no [Render](https://render.com/).Ela pode ser acessada atráves desse [link](https://todolist-rocket-s6b3.onrender.com)


## Tecnologias

- [Java](https://docs.oracle.com/en/java/javase/17/)
- [Spring](https://spring.io/projects/spring-framework)
- [BCrypt](https://docs.spring.io/spring-security/site/docs/current/api/org/springframework/security/crypto/bcrypt/BCrypt.html)
- [Spring Data](https://spring.io/projects/spring-data)
- [Docker](https://docs.docker.com/get-started/)


## Como Executar

### Localmente
- Clonar repositório git
- Construir o projeto:
```
./mvnw clean package
```
```
java -jar todolist/target/todolist-1.0.0.jar
```
A API poderá ser acessada em [localhost:8080](http://localhost:8080).

### Deploy 

API Pode está com deploy no [Render](https://render.com/) através desse [link](https://todolist-rocket-s6b3.onrender.com), as requições podem ser feitas usando o link.

## API Endpoints

Para fazer as requisições HTTP abaixo, foi utilizada a ferramenta [Postman](https://www.postman.com/):

- Post /users
- Post /tasks
- Get /tasks
- Put /task{id}
