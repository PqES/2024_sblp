# 2024_sblp
Repositório de Artefatos relacionados ao artigo "Go x Java e gRPC x REST: Um estudo empírico"

# Instruções para execução
### 1 - Compilar e execular apps Servidor
- go-http: ```cd go-http/api && go build && ./api```
- go-grpc: ```cd go-grpc/api && go build && ./api```
- java-http: ```cd java-http && ./mvnw package && java -jar target/java-http-0.0.1-SNAPSHOT.jar```
- java-grpc: ```cd java-grpc && ./mvnw package && java -jar target/java-grpc-0.0.1-SNAPSHOT.jar```

### 2 - Executar cliente
- ```cd client && go build && ./lab-client```