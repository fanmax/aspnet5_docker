# aspnet5_docker
Projeto de teste do Asp.Net 5 usando o docker

Criei este projeto para testar o Asp.Net 5 no ubuntu.

Para teste utilizei uma imagem docker para criar um container.

#Executando o docker
docker build -t yourapplication .

docker run -t -d -p 8080:5004 yourapplication
