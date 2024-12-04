# Backend - Gerenciador de Eventos (Spring Boot)

## Descrição
Este projeto é a API backend para um gerenciador de eventos, onde é possível criar e listar eventos.

## Tecnologias Utilizadas
- Java 17
- Spring Boot
- Spring Data JPA
- H2 Database

## Como Rodar o Backend
1. Clone este repositório.
2. Navegue até a pasta do backend.
3. Certifique-se de que o Java 17 está instalado.
4. Execute o comando abaixo para rodar o aplicativo Spring Boot:
    ```bash
    ./mvnw spring-boot:run
    ```
5. O servidor backend estará rodando em `http://localhost:8080`.

## Endpoints
- **POST /events**: Cria um novo evento.
- **GET /events**: Lista todos os eventos.

## Configuração do Banco de Dados
O projeto usa o **H2 Database** por padrão, mas você pode configurar outro banco de dados como MySQL se necessário.

## Como Testar
Utilize o [Postman](https://www.postman.com/) ou uma ferramenta similar para enviar requisições para o backend.