# PROJETO-DEV-JR
# 📝 API de Tarefas (To-Do)

## 📌 Descrição

Esta é uma API REST simples para gerenciamento de tarefas.
Permite criar, listar, atualizar e deletar tarefas.

O objetivo do projeto é demonstrar conhecimentos básicos de backend, API REST e integração com banco de dados.

---

## 🚀 Tecnologias utilizadas

* Python
* FastAPI
* SQLAlchemy
* SQLite

---

## ⚙️ Como rodar o projeto

### 1. Clonar o repositório

```bash
git clone https://github.com/alvsedu/PROJETO-DEV-JR.git
```

### 2. Criar ambiente virtual

```bash
python -m venv venv
venv\Scripts\activate  # Windows
source venv/bin/activate  # Linux/Mac
```

### 3. Instalar dependências

```bash
pip install -r requirements.txt
```

### 4. Rodar a aplicação

```bash
uvicorn src.main:app --reload
```

---

## 🌐 Acessar a API

* Documentação automática (Swagger):
  http://127.0.0.1:8000/docs

---

## 📦 Funcionalidades

* Criar tarefa
* Listar tarefas
* Marcar como concluída
* Deletar tarefa

---

## 📂 Estrutura do projeto

```
src/
 ├── main.py
 ├── models.py
 ├── database.py
 └── schemas.py
```

---

## 🛠️ Possíveis melhorias

* Autenticação de usuários
* Paginação
* Filtro de tarefas
* Testes automatizados
* Deploy em nuvem

---

## 🧠 Aprendizados

Este projeto reforça conceitos importantes como:

* Criação de APIs REST
* Integração com banco de dados
* Estruturação de projeto backend
* Boas práticas de código

---

## 📄 Licença

Este projeto é apenas para fins de estudo.
