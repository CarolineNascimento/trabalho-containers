# api-mensagem
Trabalho final da disciplina de Containers and Virtualization da FIAP

## Integrantes

 - Caroline Nascimento de Oliveira - 337401
- Victor Tokudo Kiam - 337385

## Requisitos

* [Java SE Development Kit 11 installed](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)
* [Docker installed](https://www.docker.com/community-edition)
* [Python 3](https://docs.python.org/3/)

## Executando

```
docker-compose up -d
```

## Testando

Depois de rodar todos os comandos com sucesso, você poderá testar localmente os endpoints:

Acessar URL e enviar requisições GET, POST, PUT, DELETE

```
http://localhost:8000/mensagens
```

### Exemplo objeto para requisição POST 

```
{
  "text": "Texto para teste da API"
}
```

