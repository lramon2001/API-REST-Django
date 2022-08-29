# API-REST-Django-
API REST desenvolvida em python utilizando o framework Django rest

## Parte 1

- Criação do projeto;
- Instalação de dependências;
- Inicialização de um projeto Django;
- Inicialização de uma aplicação;
- Criação de um banco de dados.

Para iniciar um projeto django utilizei este script:
```shell
django-admin startproject django_rest

```
Para iniciar a aplicação utilizei este script:
```shell
python manage.py startapp api

```
Para criar o banco de dados utilizei o script:

```SQL

  CREATE DATABASE django_rest

```
## Parte 2

- Criação das entidades no arquivo models.py herdando a model do Django e definindo as restrições do banco de dados
- Criação das tabelas do banco de dados

Para criar as tabelas utilizei o script:
```shell

manage.py makemigrations
```
e para que seja finalizada a migração utilizei o script:
```shell

manage.py migrate
```

## Parte 3

- Criação dos arquivos de serialização e deserialização dos dados, ou seja, esse arquivo utiliza os serializers do django_rest.


