# Trabalho 02 - Redes de Computadores

- **Aluno:** João Vitor Lopes de Farias
- **Matrícula** 180020251

## Descrição

O trabalho tem por objetivo demonstrar o uso de contêineres para fornecer um conjunto de serviços com o Docker Compose. 

## Execução

**Pré-requisitos**: [Docker](https://www.docker.com/) e [Docker Compose](https://docs.docker.com/compose/)

1. Clone o repositório
2. Na pasta raiz do projeto, execute: `docker-compose up -d`
3. Após baixar as dependências e iniciar os serviços, as aplicações estão rodando nos seguintes endereços:
   - Rocket Chat - http://localhost:4000/
   - LibreOffice - http://localhost:3000/
   - Nextcloud - http://localhost:8080/
   - Adminer -  http://localhost:8081/
4. Para interromper a execução, basta executar o seguinte comando: `docker-compose down`