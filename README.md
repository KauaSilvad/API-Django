📦 Django REST API Base
Este projeto é uma API desenvolvida com Django e Django REST Framework, pronta para ser utilizada como base para aplicações web e móveis.

🚀 Tecnologias
Python 3

Django 5.2.1

Django REST Framework 3.16.0

django-cors-headers 4.7.0

SQLite (banco de dados local)

⚙️ Funcionalidades
Estrutura inicial para criação de uma API RESTful

Middleware de CORS habilitado para permitir requisições de outros domínios

Banco de dados SQLite integrado

Pronta para deploy ou desenvolvimento local

📁 Estrutura do Projeto
pgsql
Copiar
Editar
.
├── manage.py               # Script de gerenciamento do Django
├── db.sqlite3              # Banco de dados local SQLite
├── requirements.txt        # Dependências do projeto
└── api_root/               # Diretório principal com as configurações do projeto (não enviado)
🛠️ Como executar
Clone o repositório:

bash
Copiar
Editar
git clone https://github.com/KauaSilvad/API-Django.git
cd API-Django
Crie um ambiente virtual e ative:

bash
Copiar
Editar
python -m venv venv
source venv/bin/activate  # No Windows: venv\Scripts\activate
Instale as dependências:

bash
Copiar
Editar
pip install -r requirements.txt
Rode o servidor local:

bash
Copiar
Editar
python manage.py runserver
Acesse a API em: http://127.0.0.1:8000/

📌 Requisitos
Python 3.10 ou superior

Pip
