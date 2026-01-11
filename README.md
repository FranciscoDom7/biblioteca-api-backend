# Sistema de Gestão de Biblioteca API

**Tema:** Sistema de controle bibliográfico.

## Tecnologias Utilizadas
- **Backend:** Python 3, Django REST Framework.
- **Frontend:** Vue.js, Axios, Vite.
- **Banco de Dados:** SQLite (Desenvolvimento).

## Diagrama de Entidades (Relacionamentos)
1. **Categoria** (1) ---- (N) **Livro**
2. **Autor** (N) ---- (M) **Livro**
3. **Membro** (1) ---- (N) **Emprestimo**
4. **Livro** (1) ---- (N) **Emprestimo**

## Instruções de Teste
1. Clone o repositório.
2. Crie um ambiente virtual: `python -m venv venv`.
3. Ative o venv e instale as dependências: `pip install -r requirements.txt`.
4. Execute as migrações: `python manage.py migrate`.
5. Inicie o servidor: `python manage.py runserver`.
6. Acesse a API em: `http://127.0.0.1:8000/api/`.

**Estudante:** Chiquito Samanjata Francisco Cacuata
**Ano:** Quarto ano
**Curso** Informatica.
