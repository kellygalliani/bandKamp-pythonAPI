# BandKamp 

- Api no estilo BandCamp - para artistas independentes gerenciarem seus álbuns e músicas lançadas e possibilitar usuários não admin a consumirem e visualizarem esses álbuns e músicas de seus artistas favoritos.

Este é um projeto criado em Python usando o Django Rest Framework.

## DEPLOY DA API - Documentação 

https://m5-bandkamp-generic-view-kelly.onrender.com/api/docs/redoc/.

## Pré-requisitos

- Python 3.6 ou superior
- pip

## Instalação

1. Clone o repositório:
```bash
git clone https://github.com/meu-usuario/meu-projeto.git
```
2 - Entre no diretório do projeto:
```bash
cd meu-projeto
```

3 - Crie um ambiente virtual:
```bash
python -m venv venv
```

4 - Ative o ambiente virtual:
```bash
# Linux:
source venv/bin/activate

# Windows (Powershell):
.\venv\Scripts\activate

# Windows (Git Bash):
source venv/Scripts/activate

```
5 - Instale as dependências:
```
pip install -r requirements.txt
```

6 - --Execução--
Para executar o servidor de desenvolvimento, use o seguinte comando:
```
python manage.py runserver
```
Isso iniciará o servidor na porta 8000. Você pode acessar a API em http://localhost:8000/.

7 - Testes
Para executar os testes usando o pytest, siga estas etapas:
    1- Instale os pacotes pytest, pytest-testdox e pytest-django:
      
      ```pip install pytest pytest-testdox pytest-django```
   
   2- Execute os testes no diretório principal do projeto:
      
      ```pytest --testdox -vvs```

## Deselvolvedora

- <a name="kelly" href="https://www.linkedin.com/in/kelly-cristina-galliani/" target="_blank">Kelly Cristina</a>

<a name="termos"></a>

## Termos de uso

Este é um projeto Open Source para fins educacionais e não comerciais, **Tipo de licença** - <a name="mit" href="https://opensource.org/licenses/MIT" target="_blank">MIT</a>


