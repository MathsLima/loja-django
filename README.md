# loja-django
Sistema de E-comerce com Python e Django

### Arquitetura do Django
 - Model: mapeamento do banco de dados do projeto
 - Template: página de visualização dos dados, onde fica o HTML que será renderizado no navegador
 - View: recebe uma requisição web e retorna uma resposta web


#### criação do ambiente virtual
```
cria o ambiente virtual: python -m venv env

altera a privacidade do código: Set-Executionpolicy -Scope Process -ExecutionPolicy ByPass

ativa o ambiente virtual: .\env\Scripts\activate

cria a estrutura básica do projeto: django-admin startproject setup .

executa o ambiente web Django: python manage.py runserver
```

#### criaçao do projeto
```
cria o projeto: django-admin startproject loja

inicia a aplicaçao: python manage.py startapp main 
```

#### migrate
```
python manage.py makemigrations
python manage.py migrate
```

#### cria o admin 
```
py manage.py createsuperuser
```

## Etapas
```
1 - inserir a main em setup>setting>installed-apps e fazer as migrações pelo terminal
2 - criação das classes category, cor, tamanho, size em main>models 
3 - criação da classe product utilizando as calsses acima em main>models 
4 - registro das classes em admin.py
5 - fazer makemigrations e migrate após cria e registrar as classes 
```