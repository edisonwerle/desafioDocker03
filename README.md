# desafioDocker03
Desafio 3 do curso de docker

Para rodar o container use:

docker run -d \
  --name curso_mongo \
  -e MONGO_INITDB_ROOT_USERNAME=mongo_usr \
  -e MONGO_INITDB_ROOT_PASSWORD=mongo_pwd \
  -p 27017:27017 \
  mongo:6.0

Ou com compose use o arquivo compose.yml e rode:
docker compose up -d
