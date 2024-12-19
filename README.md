# Imersão Fullcycle 20 - Sistema de rastreamento de veículos


## Rodar a aplicação



## Arquitetura do projeto
![alt text](./arquitetura_projeto.png)


## para subir o docker
	docker compose up
	docker compose up -d
	para baixar: docker compose down


## outros comandos
	doker compose ps


## baixa as dependencias go
	go mod tidy
	


##### para rodar todo o projeto ####   
	docker compose up -d

    entrar no nest-http
        docker compose exec nest bash
        yarn start:dev

    entrar no nest-consumer
        docker compose exec nest bash
        yarn start:dev -- --entryFile=cmd/kafka.cmd

    entrar no go-simulator
        docker compose exec simulator  bash
        go run cmd/simulator/main.go
    entrar no next  
        docker compose exec next bash
        yarn dev
