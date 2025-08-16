# Spring Boot

## Instruções

### Criar o banco de dados
```
createdb apirest-springboot-v4
psql apirest-springboot-v4
```

### Criar usuário e permissões
```
CREATE USER postgres WITH PASSWORD 'banco123';
CREATE DATABASE productsapi OWNER postgres;
GRANT ALL PRIVILEGES ON DATABASE productsapi TO postgres;
```

