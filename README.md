# ORIGIN SGA API

## Pré-requisito

Antes de rodar o projeto é necessário que você tenha instalado na sua máquina o * **[Docker](https://www.docker.com/) (docker compose)** - Para instalar o docker, [consulte a documentação oficial](https://docs.docker.com/engine/installation/) de acordo com seu sistema operacional.

## Instalando

Faça o fork do projeto em [UNIVESP](https://github.com/univesp/sou-syslog-api)

### Desenvolvimento

Após os passos descritos acima:

**1**. Clone o projeto que realizou o fork e entre nele
```
$ git clone https://github.com/baraodev/sou-syslog-api
$ cd sou-syslog-api
```

**2**. Baixe o .env no [Drive](https://drive.google.com/a/univesp.br/file/d/1tELg6ew2WmL_glhGw32xNI7z-qWbx9gp/view?usp=sharing) (Acesso a este link está disponível apenas para mantenedores) e adicione na raíz do projeto

**3**. Para instalar as dependências, execute
```
$ npm install ou yarn
```

**4**. Inicie a aplicação
```
$ docker-compose up --build
```

Este comando com o parametro '--build' é necessário somente a primeira vez que usar a aplicação após buildar uma vez use:
```
$ docker-compose up
```

## Usando a API

Para acessar os endpoints da aplicação, siga estes passos:

**1**. Inicie a aplicação
```
$ docker-compose up --build
```

**2**. Consulte a documentação da API

**[Documentação Origin SGA API::v1](https://github.com/univesp/sou-syslog-api/blob/devel/docs/syslogV1.md)**

## Contribuindo

Acesse o arquivo **[CONTRIBUTING](https://github.com/univesp/sou-syslog-api/blob/devel/CONTRIBUTING.md)** para obter informações de como contribuir.

## Construído com

*[Node.js 10.15.0](https://nodejs.org/en/)

*[Express.js 4.16.4](https://expressjs.com/)

## Mantenedores

[Marco Barão](https://github.com/baraodev)

[Marcus Vinicius](https://github.com/mviniciuscoimbra)

[Robson Arruda](https://github.com/robsonarruda1)
