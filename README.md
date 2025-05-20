# 🎶 a4tunados-test-project

Plataforma de aulas online para professores de música, desenvolvida como parte do desafio técnico da empresa **a4tunados**.

Professores podem cadastrar aulas em vídeo de forma privada, enquanto alunos têm acesso apenas aos vídeos dos seus professores. O foco é em um MVP funcional e enxuto.

---

## 📁 Estrutura do Projeto

Este repositório agrupa dois subprojetos:

- [`frontend`](./frontend) – Aplicação em Next.js
- [`backend`](./backend) – API com Django + PostgreSQL

---

## 🧩 Clonando o Projeto com Submódulos

Para clonar o projeto corretamente com os submódulos, use:

```bash
git clone --recurse-submodules https://github.com/seu-usuario/a4tunados-test-project.git
cd a4tunados-test-project
```

Caso já tenha clonado o repositório sem --recurse-submodules, rode:

```bash
git submodule update --init --recursive
```

## ▶️ Rodando o Projeto
### 🔧 Backend (Django)

```bash
cd backend
python -m venv venv
source venv/bin/activate  # no Windows: venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

### 💻 Frontend (Next.js)

```bash
cd frontend
npm install
npm run dev
```

## 🚀 Tecnologias
Next.js +
Django + Django REST Framework +
PostgreSQL

## 📆 Entrega
Entrega até 22/05 às 18h

Desenvolvido por João para o desafio técnico da a4tunados.
