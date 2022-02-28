# API Com Flask

## Tecnologias

* Python
* Flask
* Pydantic
* TinyDB

## Idéia do Projeto

É um simples CRUD com Flask utilizando TinyDB como banco de dados, e documentando o projeto e seus endpoints com Pydantic Spec para utilização do Swagger como gerador de documentação para a API.

Para visualizar todas as rotas basta acessar:

* http:localhost:5000/apidoc/swagger

## Como rodar o projeto?

Para rodar o projeto basta instalar as dependências localizadas no arquivo Pipfile, pode utilizar o Pipenv, bastando digitar:

```
  Pipenv Install
```

Depois execute Pipenv shell para executar o ambiente virtual:

```
  Pipenv shell
```

E por fim execute flask run para rodar o servidor do projeto:

```
  flask run
```

Feito durante a live do Eduardo Mendes. [Link da live](https://www.youtube.com/watch?v=1_nQ5A2HcgU)  
