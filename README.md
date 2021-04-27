# Full Cycle - Docker

## Desafio 01

Go Lang

### Imagem Docker Hub

https://hub.docker.com/r/andersonigorf/codeeducation

```bash        
  docker pull andersonigorf/codeeducation
```

### Rodar a aplicação

Execute o comando:

```bash
  docker run andersonigorf/codeeducation
```

## Desafio 02

Nginx + Node.js + MySQL

### Rodar a aplicação

Execute os comandos:

```bash

  # 1 - Clonar o repositório do projeto
  git clone https://github.com/andersonigorf/fullcycle-docker.git

  # 2 - Acessar o diretório nginx-node
  cd nginx-node

  # 3 - Executar o docker compose (Aguardar inicialização dos containers)
  docker-compose up -d

  # 4 - Acessar a aplicação
  http://localhost:8080
```