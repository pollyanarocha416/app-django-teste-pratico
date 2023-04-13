# Acriacão do projeto
1. o primeiro passo foi criar o ambiente virtual (venv)
comando: py -m venv venv
2. iniciar a venv com o comando
comando: .\venv\Scripts\activate
3. Baixar dependencias
comandos: pip install django, pip freeze > requirements.txt,
pra instalaçao das dependencias: pip install -r requirements.txt
4. Criar Projeto: django-admin startproject organiza .
5. Criar App: python manage.py startapp fotos
6. Pra iniciar o projeto: python manage.py runserver, ctrl + c pra sair 
