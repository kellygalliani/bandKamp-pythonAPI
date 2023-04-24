# BandKamp 

- Api no estilo BandCamp - para artistas independentes gerenciarem seus álbuns e músicas lançadas e possibilitar usuários não admin a consumirem e visualizarem esses álbuns e músicas de seus artistas favoritos.

Este é um projeto criado em Python usando o Django Rest Framework.

## Pré-requisitos

- Python 3.6 ou superior
- pip

## Instalação

1. Clone o repositório:
```bash
git clone https://github.com/meu-usuario/meu-projeto.git

2 - Entre no diretório do projeto:
cd meu-projeto

3 - Crie um ambiente virtual:
python -m venv venv

4 - Ative o ambiente virtual:
# Linux:
source venv/bin/activate

# Windows (Powershell):
.\venv\Scripts\activate

# Windows (Git Bash):
source venv/Scripts/activate

5 - Instale as dependências:
pip install -r requirements.txt

6 - --Execução--
Para executar o servidor de desenvolvimento, use o seguinte comando:

python manage.py runserver

Isso iniciará o servidor na porta 8000. Você pode acessar a API em http://localhost:8000/.

7 - Testes
Para executar os testes usando o pytest, siga estas etapas:

    1- Instale os pacotes pytest, pytest-testdox e pytest-django:
      pip install pytest pytest-testdox pytest-django
    2- Execute os testes no diretório principal do projeto:
      pytest --testdox -vvs

---- DOCUMENTAÇÃO -----

A documentação da API está disponível em http://localhost:8000/docs/.

---- DEPLOY DA API ----  

https://m5-bandkamp-generic-view-kelly.onrender.com/api/docs/redoc/.

