
# Queue API

## Descrição

Este projeto consiste em uma api de criação de filas do tipo FIFO, onde é possível enfileirar 3 tipos de mensagens. Voz, E-mail e Chat.

## Como Usar

### Pré-requisitos

- Docker instalado em seu sistema. [Instruções de instalação do Docker](https://docs.docker.com/get-docker/)
- Navegador da web para acessar a documentação Swagger.

### Passos para Executar a Aplicação com Docker

1. **Pull da Imagem Docker:**
   ```
   docker pull lorenzo2017/queue_api:latest
   ```

2. **Executar o Contêiner Docker:**
   ```
   docker run -p 8000:8000 lorenzo2017/queue_api:latest
   ```

3. **Acessar a Documentação Swagger:**
   Após iniciar o contêiner, você pode acessar a documentação Swagger em:
   [http://localhost:8000/swagger-ui/index.html](http://localhost:8000/swagger-ui/index.html)

   Aqui você encontrará detalhes sobre os endpoints da API e como usá-los.
