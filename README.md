# MovieFlix

Nosso agradecimento a:

	Sergio Danilo Jr.

## Requisitos

- Docker Engine instalado na máquina
- Docker Compose
- Editor de Texto para códigos (e.g. Visual Studio Code)
- Persistência

## Comandos Docker básicos para gerenciar o Projeto

### Listando os containers daquela pasta em questão

```bash 
    $ docker-compose ps
```

### Listando todos os containers em execução na sua máquina

```bash 
    $ docker ps
```

### Subindo o container

```bash 
    $ docker-compose up -d
```

> A diretiva ```-d``` serve para que o Docker não trave o seu terminal, portanto, entre no modo ```detatched```

### Derrubando os containers de serviços

```bash 
    $ docker-compose down
```

### Restartando os containers de serviços

```bash 
    $ docker-compose restart
```

### Removendo a execução de todos os containers ativos da sua máquina

```bash 
    $ docker rm -f $(docker ps -a -q)
```
