# ProjetoBD
Imobi - Site para aluguel de casa feito em Django
Para utilizar o programa, primeiro crie um banco de dados em postgresql com as seguitnes informações:
```python
'NAME': 'Imobi', 
'USER': 'postgres', 
'PASSWORD': '1234'
'HOST': '127.0.0.1', 
'PORT': '5432',
```        
A seguir escreva na linha de comando:
```python
python manage.py makemigrations
python manage.py migrate
```
Ademais, crie um super usuário utilizando o comando:
```python
python manage.py createsuperuser
```
Por fim, para iniciar a aplicação utilize:
```python
python manage.py runserver
```
E a aplicação inicializará em LocalHost
