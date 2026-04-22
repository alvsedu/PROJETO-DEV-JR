# 📘 Documentação da API

## 🔹 Criar tarefa

**POST** /tasks

### Request

```json
{
  "title": "Estudar API"
}
```

### Response (201)

```json
{
  "id": 1,
  "title": "Estudar API",
  "completed": false
}
```

---

## 🔹 Listar tarefas

**GET** /tasks

### Response (200)

```json
[
  {
    "id": 1,
    "title": "Estudar API",
    "completed": false
  }
]
```

---

## 🔹 Marcar tarefa como concluída

**PUT** /tasks/{id}

### Response (200)

```json
{
  "id": 1,
  "title": "Estudar API",
  "completed": true
}
```

### Erro (404)

```json
{
  "detail": "Task not found"
}
```

---

## 🔹 Deletar tarefa

**DELETE** /tasks/{id}

### Response (200)

```json
{
  "message": "Task deleted"
}
```

### Erro (404)

```json
{
  "detail": "Task not found"
}
```

---

## ⚠️ Códigos HTTP utilizados

* 200 → Sucesso
* 201 → Criado com sucesso
* 404 → Não encontrado
* 500 → Erro interno

---

## ❗ Tratamento de erros

* Retorna erro quando a tarefa não existe
* Validação automática via FastAPI (dados inválidos)

