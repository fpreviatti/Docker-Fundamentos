##Montar a imagem:

mvn spring-boot:build-image

##Run:

docker run -d -p 8080:8080 projeto:0.0.1-SNAPSHOT

##Adicionando TAG: 

docker tag 97626deded53 projeto-classificados

##Push para o Docker Hub

docker push abubleh/classificados:latest

Caso seja usado WSL -> Deverá importar o container em linux no Azure também
