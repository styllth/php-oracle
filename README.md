# Docker PHP com Apache e Oracle oci8 (instantclient 12.2.0.1.0)

Esta imagem foi criada a partir de [imagens PHP oficiais](https://hub.docker.com/_/php/).

Ele adiciona drivers oci8 à imagem oficial para se conectar ao banco de dados Oracle.

## Instruções

### Para rodar

```bash
docker-compose up -d
```

### Para parar

```bash
docker-compose stop
```

### Para Remover

```bash
docker-compose down
```

## Acessando com SQL Developer

### Para acesar o banco de dados usando o Oracle SQL Developer

```bash
host:localhost
port:1521
user:usuario
pass:senha
```

## Testar a conexão

Teste a conexão como banco em: [localhost/teste.php](http://localhost/teste.php)
