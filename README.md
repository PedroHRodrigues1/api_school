# Escola API com Django 3 e Django Rest Framework

Este projeto é uma API construída usando Django 3 e Django Rest Framework, conforme aprendido no curso da Alura sobre API com Django 3.

## Descrição

A API gerencia informações relacionadas a uma escola, incluindo alunos, cursos e matrículas. Os recursos principais incluem:

- Alunos: Informações sobre os alunos, como nome, e-mail e cursos matriculados.
- Cursos: Detalhes sobre os cursos oferecidos pela escola.
- Matrículas: Relaciona alunos a cursos específicos.

## Requisitos do Sistema

Certifique-se de ter os seguintes requisitos instalados em seu ambiente de desenvolvimento:

- Python 3.11.7
- Django 3.0.7
- Django Rest Framework 3.14.0

## Configuração do Ambiente

1. Clone este repositório:

   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   ```

2. Crie e ative um ambiente virtual:
```
python -m venv venv
source venv/bin/activate   # Para Linux/Mac
```
```
# ou
.\venv\Scripts\activate    # Para Windows
```

3. Instale as dependências do projeto:

```
pip install -r requirements.txt
```

## Configuração do Banco de Dados:

1. Aplique as migrações:
```
python manage.py migrate
```

2. Crie um superusuário para acessar o painel de administração:
```
python manage.py createsuperuser
```
3. Siga as instruções para criar um superusuário no prompt (CMD).

## Inicie o servidor de desenvolvimento:
```
python manage.py runserver
```

## Acesse o painel de administração em http://127.0.0.1:8000/admin/ e faça login com as credenciais do superusuário.

## Endpoints da API
A API estará disponível em http://127.0.0.1:8000/api/. Consulte a documentação da API para obter detalhes sobre os endpoints e como usá-los.

## Documentação da API
A documentação detalhada da API pode ser encontrada em http://127.0.0.1:8000/swagger/ ou http://127.0.0.1:8000/redoc/.


