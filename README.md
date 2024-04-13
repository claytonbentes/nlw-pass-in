# Pass-In API

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)

Este projeto é uma API criada usando **Python, Flask, SQLAlchemy, SQLite como banco de dados.**

Projeto desenvolvido na Trilha de Python da NLW Unite da Rocketseat.


## Instalação

1. Clone o repositório:

```bash
git clone https://github.com/claytonbentes/nlw-pass-in
```

2. Instale os pacotes usando o comando:

```bash
pip install -r requirements.txt
```

## Rodando o aplicativo

1. Inicie o aplicativo com:
```bash
python app.py
```
3. A API poderá ser acessada em http://localhost:3000

## API Endpoints
A API fornece os seguintes endpoints:

```markdown
POST /events - Registre um novo evento.

GET /events/:event_id - Recupera detalhes do evento.

GET /events/:event_id/attendees - Recupera a lista de participantes registrados para o evento especificado.

POST /events/:event_id/register - Registre um novo participante no evento.

POST /attendees/:attendee_id/badge - Recupera o crachá do participante para acessar o evento.

POST /attendees/:attendee_id/check-in - Faça o check-in do participante no evento.
```

## Contato

[![](https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/claytonbentes/)
[![](https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white)](mailto:claytonjhony.bentes@gmail.com)
