# Comandos Conteiners Docker

***docker run:*** Executa um comando em um novo container a partir de uma imagem Docker.
```
docker run -it <image_name> bash
```
***docker ps -a:*** Lista containers em execução e parados no seu sistema.
```
docker ps -a
```
***docker container ls:*** Lista todos os containers docker em execução no seu sistema.
```
docker container ls
```
***docker exec:*** Executa um comando dentro de um container em execução.
```
docker exec -it <container_name/id> bash
```
***docker stop:*** Para um container em execução de forma controlada.
```
docker stop <container_name/id>
```
***docker kill:*** Para um container em execução de forma forçada.
```
docker kill <container_name/id>
```
***docker rm:*** Remove um container parado do seu sistema.
```
docker rm <container_name/id>
```
***docker start:*** Inicia um container parado.
```
docker start <container_name/id>
```
***docker pause:*** Suspende a execução de um container.
```
docker pause <container_name/id>
```
***docker unpause:*** Retorna a execução de um container suspenso.
```
docker pause <container_name/id>
```
***docker top:*** Mostra os processos em execução dentro de um container em execução.
```
docker top <container_name/id>
```
***docker logs:*** Exibe os logs de um container em execução.
```
docker logs
```
***docker diff:*** Mostra as diferenças entre estado atual de um container e o seu estado em um commit anterior.
```
docker diff <container_name/id>
```
***docker cp:*** Copia arquivos entre um host e um container ou entre containers.
```
docker cp <file.txt> <container_name/id> :/path/to/file.txt
```
***docker export:*** Exporta o sistema de arquivos de um container para um arquivo tar.
```
docker export container_name > another_container.tar
```