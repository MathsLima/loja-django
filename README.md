# loja-django
Sistema de E-comerce com Python e Django



#### criação do ambiente virtual
```
cria o ambiente virtual: python -m venv .venv

altera a privacidade do código: Set-Executionpolicy -Scope Process -ExecutionPolicy ByPass

ativa o ambiente virtual: .\.venv\Scripts\activate

cria a estrutura básica do projeto: django-admin startproject setup .

executa o ambiente web Django: python manage.py runserver
```

#### criaçao do projeto
```
cria o projeto: django-admin startproject loja

inicia a aplicaçao: python manage.py startapp main 
```

#### cria o migrate
```
python manage.py migrate
```

#### cria o admin 
```
py manage.py createsuperuser
```