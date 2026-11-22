
# API de Livros - Flask

## Objetivo
Desenvolver uma API utilizando Python e Flask
que retorna informações de três livros em JSON.

## Tecnologias
- Python
- Flask

## Instalação
python -m venv venv

venv\Scripts\activate.bat

pip install -r requirements.txt

## Execução
python app.py

## Rota
GET /livros

http://127.0.0.1:5000/livros

## Funcionalidades
A API retorna três livros contendo:
- id
- titulo
- autor
- ano



## Front-End

O projeto possui uma interface web desenvolvida
com HTML, CSS e JavaScript.

A interface consulta a API Flask e apresenta
os três livros em cartões.

Para acessar o Front-End, execute:

python app.py

Depois abra no navegador:

http://127.0.0.1:5000/

## Back-End

Para consultar os dados em JSON:

http://127.0.0.1:5000/livros
