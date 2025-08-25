# Olhar Empresarial — Blog de Tecnologia e Negócios

Um blog desenvolvido em Django com Tailwind CSS e SQLite, criado para explorar tendências, práticas e inovações no mundo da tecnologia e dos negócios.
A aplicação traz posts categorizados (tecnologia, economia, política, etc.), organizados em uma estrutura limpa e escalável.

Repositório oficial: [Olhar Empresarial — Blog](https://github.com/CrazyAsura/Olhar-Empresarial---Blog)

## 🛠 Tecnologias Utilizadas

Backend: Django (Python)
Frontend: Tailwind CSS (design responsivo e moderno)
Banco de Dados: SQLite (simples e eficiente para projetos em desenvolvimento)

## ⚙️ Instalação e Configuração

### 1. Clone o repositório

```bash
git clone https://github.com/CrazyAsura/Olhar-Empresarial---Blog.git
cd Olhar-Empresarial---Blog
```

### 2. Crie e ative o ambiente virtual

- Windows:
```bash
python -m venv env
env\Scripts\activate
```
- Linux/Mac:
```bash
python3 -m venv env
source env/bin/activate
```

### 3. Instale as dependências

```bash
pip install -r requirements.txt
```

### 4. Configure o banco de dados

```bash
python manage.py migrate
```

### 5. Inicie o servidor

```bash
python manage.py runserver
```

➡️ Depois acesse no navegador: http://127.0.0.1:8000

## 📝 Como Usar

Acesse a página inicial para navegar pelos posts.
Utilize o painel administrativo do Django (/admin) para gerenciar posts, categorias e usuários.
Categorias já disponíveis: Tecnologia, Economia, Política.
Posts ilustrativos podem ser encontrados na pasta posts/.

## 📂 Estrutura do Projeto

```
Projeto-1/
│
├── blog/                  # Aplicação principal do blog
│   ├── migrations/        # Controle de versões do banco de dados
│   ├── templates/         # Templates HTML renderizados pelo Django
│   ├── admin.py           # Configurações do painel administrativo
│   ├── apps.py            # Configuração da aplicação 'blog'
│   ├── forms.py           # Formulários para interações do usuário
│   ├── models.py          # Modelos (tabelas do banco de dados)
│   ├── tests.py           # Testes automatizados
│   ├── urls.py            # Rotas da aplicação 'blog'
│   └── views.py           # Lógica das páginas e APIs
│
├── categories/            # Imagens para categorias (economia, política, etc.)
│
├── NewJornal/             # Configuração principal do projeto Django
│   ├── __pycache__/       
│   ├── __init__.py        
│   ├── asgi.py            # Configuração ASGI
│   ├── settings.py        # Configurações globais do Django
│   ├── urls.py            # Rotas principais do projeto
│   └── wsgi.py            # Configuração WSGI (deploy)
│
├── posts/                 # Repositório de imagens dos posts
│
├── db.sqlite3             # Banco de dados local
├── manage.py              # Gerenciador de comandos do Django
└── README.md              # Documentação do projeto
```

## 📌 Autor

Projeto desenvolvido por Leon.
