# Orientações Gerais

## Primeiro passo: Definir enviroments
Abra o arquivo [.env](.env) com um editor de texto e edite o que achar pertinente.

Aconselho alterar apenas o que esta definido com o sufixo **_DATA** que são os mapeamentos dos *volumes*	
	
## Segundo passo: Buildar
```sh
docker-compose build
```

## Terceiro passo: Subindo os containers
```sh
docker-compose up -d
```
## Quarto passo: Checando os containers
```sh
docker-compose ps
```
## Quinto passo: Hands on
Todas as senhas, estão definidas como: **Senha123**

### Rabbit MQ
- **url:** http://localhost:15672/
- **postas:** 5672 / 15672
- **usuario:** admin

### PostgreSQL
- **url:** jdbc:postgresql://localhost:5432/
- **portas:** 5432
- **usuario:** postgres


### PGAdmin4
- **url:** http://localhost:9980/
- **portas:** 9980
- **usuario:** rodolfo.maisvida@gmail.com


### MongoDB
- **url:** mongodb://root:Senha123@localhost:27017/test?authSource=admin&ssl=false
- **portas:** 27017
- **usuario:** root
