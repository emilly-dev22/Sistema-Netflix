# Sistema-Netflix
Sistema Netflix/LetterBox

# Sistema Netflix/Letterboxd

Sistema para gerenciar catálogo de filmes e séries, onde usuários podem avaliar conteúdos e navegar por gêneros, inspirado nas plataformas Netflix e Letterboxd.

---

## Tecnologias utilizadas

- Python 3.x  
- SQLAlchemy (ORM para banco de dados)  
- SQLite (banco de dados local)  
- Programação Orientada a Objetos (POO)  
- Ambiente Virtual Python (virtualenv ou venv)  

---

## Estrutura do Projeto

- `main.py`: Arquivo principal que contém o menu e integração das funcionalidades.  
- `models.py`: Definição das classes do sistema (Catálogo, Filme, Série, Gênero, Avaliação, Usuário).  
- `database.py`: Configuração e conexão com o banco de dados usando SQLAlchemy.  
- `README.md`: Documentação do projeto.  

---

## Funcionalidades

- Cadastro, listagem, edição e remoção de usuários.  
- Cadastro, listagem, edição e remoção de filmes e séries.  
- Cadastro, listagem, edição e remoção de avaliações vinculadas aos conteúdos.  
- Associação de conteúdos com gêneros via relacionamento N:N.  
- Validação das notas das avaliações (de 1 a 10).  

---

## Como usar

1. Clone o repositório:  
   ```bash
   git clone https://github.com/emilly-dev22/Sistema-Netflix.git
   cd Sistema-Netflix

2. Crie e ative o ambiente virtual:
python -m venv venv
.\venv\Scripts\Activate.ps1

3.Instale as dependências
pip install -r requirements.txt

4.Execute o sistema
python main.py
