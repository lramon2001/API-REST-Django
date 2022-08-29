# API-REST-Django 
API REST 📚🐍 -desenvolvida em python utilizando o framework Django rest
<div style="display: inline_block" align="center"><br>
  <img align="center" alt="Judeu-Js" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/django/django-plain.svg">
  <img align="center" alt="Judeu-React" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg">
  


 </div>

## Para testar a API basta seguir os passos:

Passo 1-Clonar o repositório:

```shell
git clone https://github.com/lramon2001/API-REST-Django.git
```
Passo 2- Entrar no diretório com o arquivo manage.py:

```shell
cd  api_rest_django
```

Passo 3- Iniciar o servidor

```shell
python manage.py runserver
```

Passo 4- Brincar com o postman fazendo requisições nas rotas especificadas em urls


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

## Parte 4 
- Criação do método listar todas tecnologias
- Criando requisições utilizando o Postman

Para levantar o servidor utilizei o script
```shell
 python manage.py runserver
 ```
## Parte 4 
- Criação do método cadastrar tecnologias
- Criação do método exibindo tecnologia por ID

## Parte 5
- Removendo Tecnologia

## Parte 6
- Listando vagas
- Cadastrando vaga

## Parte 7
- Exibindo vaga por ID
- Removendo vaga


