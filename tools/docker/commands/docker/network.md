# Comandos Network Docker

***docker network create:*** Cria uma nova rede Docker.
```
docker network create <network_name>
```
***docker network ls:*** Lista as redes Docker disponíveis em seu sistema.
```
docker network ls
```
***docker network inspect:*** Exibe informações detalhadas sobre uma rede Docker.
```
docker network inspect <network_name>
```
***docker network rm:*** Remove uma rede Docker do seu sistema.
```
docker network rm <network_name>
```
***docker connect:*** Conecta um container a uma rede Docker.
```
docker connect <network_name> <container_name/id>
```
***docker disconnect:*** Desconecta um container de uma rede Docker.
```
docker disconnect <network_name> <container_name/id>
```