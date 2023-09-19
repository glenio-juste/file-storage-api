<h1 align="center">
  File Storage API
</h1>

Implementação de um servidor de armazenamento de arquivos utilizando Spring Boot.

## Tecnologias
 
- [Spring Boot](https://spring.io/projects/spring-boot)
- [Spring MVC](https://docs.spring.io/spring-framework/reference/web/webmvc.html)

## Como Executar

- Clonar repositório git:
```
git clone https://github.com/glenio-juste/file-storage-api.git
```
- Para construir o projeto:
```
./mvnw clean package
```
- Para executar:
```
java -jar ./target/file-storage-api-0.0.1-SNAPSHOT.jar
```

## Para testar Endpoints

- Upload file:
```
http://localhost:8080/api/files/upload

No form-data digitar "file". Um botão aparece para você selecionar o arquivo desejado.
```
- Download file:
```
http://localhost:8080/api/files/download/Lorem Ipsum.pdf
```
- List uploaded files:
```
http://localhost:8080/api/files/list
```
