# API de Cadastro de Livros para Biblioteca

## Descrição
Esta API RESTful foi criada para gerenciar o cadastro de livros em uma biblioteca. Ela permite operações de criar, ler, atualizar e excluir informações sobre livros, facilitando o gerenciamento do acervo de uma biblioteca.

## Tecnologias Utilizadas
- Python
- Django
- Django Rest Framework

## Instalação e Configuração
Para configurar e rodar a API localmente, siga os passos abaixo:

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/api-cadastro-livros.git

2. Navegue até o diretório do projeto:
   ```bash
   cd api-cadastro-livros

3. Crie um ambiente virtual:
   ```bash
   python -m venv venv

4. Ative o ambiente virtual:
   ```bash
   source venv/bin/activate  # No Windows use `venv\Scripts\activate`

5. Instale as dependências:
   ```bash
   pip install -r requirements.txt

6. Realize as migrações:
   ```bash
   python manage.py migrate

7. Inicie o servidor:
   ```bash
   python manage.py runserver
