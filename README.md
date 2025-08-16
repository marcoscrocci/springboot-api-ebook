# Spring Boot

## Instruções

### Vídeo do curso
#### Spring Boot 3 | Curso Completo 2023
https://www.youtube.com/watch?v=wlYvA2b1BWI


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

### Gerar o projeto inicial
```
https://start.spring.io/
```

