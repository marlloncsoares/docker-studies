# docker-studies
Estudos sobre o Docker.

## Comandos no docker

~~~shell
$ docker ps [OPTIONS] -> O comando lista contêineres ativos.

Opções:
--all, -a -> Mostrar todos os contêineres (o padrão mostra apenas em execução)

--filter , -f ->  Filtre a saíde com base nas condições fornecidas
~~~

Executando terminal dentro do container
~~~shell
$ docker container exec -it [NOME DO CONTAINER] /bin/sh
~~~