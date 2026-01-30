# 🚀 Projeto Flask CRUD Seguro

Sistema Web desenvolvido com **Flask + MySQL**, seguindo boas práticas de **segurança, organização MVC OU CRUD e interface profissional com Bootstrap**.

---

## 🖼️ Demonstração
<p align="center"> <img src="Crud1.jpg" width="700"/> <br><br> <img src="Crud2.jpg" width="700"/>  <br><br> <img src="Crud3.jpg" width="700"/></p>



## 📌 Funcionalidades

✔ Login com sessão segura
✔ Perfis de acesso (**Admin / Usuário**)
✔ CRUD completo (Create, Read, Update, Delete)
✔ Busca com formulário
✔ Edição com **Modal Bootstrap**
✔ Senhas protegidas com **hash (Werkzeug)**
✔ Interface responsiva e profissional
✔ Estrutura organizada em **CRUD**

---

## 👥 Perfis de Usuário

### 🔑 Administrador

* Gerenciar usuários
* Criar, editar e excluir registros
* Visualizar todos os dados

### 👤 Usuário

* Acesso ao sistema
* Visualização e operações permitidas pelo admin

> O perfil pode ser facilmente expandido para permissões mais avançadas.

---

## 🔎 Buscar com Formulário

* Campo de busca por **nome ou e-mail**
* Filtro dinâmico via GET
* Implementado diretamente no dashboard

```html
<form method="GET" class="d-flex">
  <input name="search" class="form-control" placeholder="Buscar...">
</form>
```

---

## ✏️ Editar com Modal Bootstrap

* Modal aberto sem sair da página
* Dados carregados dinamicamente
* Experiência de usuário moderna

```html
<button data-bs-toggle="modal" data-bs-target="#editModal">Editar</button>
```

---

## 🧱 Arquitetura 

```
app.py            <- Controller principal
templates/        <-Views (HTML + Bootstrap)
static/           <- CSS / JS
.env              <-Variáveis de ambiente
requirements.txt  <-Dependências
```

* **Model**: MySQL + PyMySQL
* **View**:  Bootstrap
* **Controller**: Flask Routes

---

## 🔐 Segurança

* Sessões protegidas com `SECRET_KEY`
* Senhas criptografadas com `generate_password_hash`
* Controle de acesso por sessão
* Variáveis sensíveis em `.env`

```python
app.secret_key = os.getenv("SECRET_KEY")
```

---

## 🛠️ Tecnologias Utilizadas

* Python 3
* Flask
* MySQL
* PyMySQL
* Bootstrap 5
* HTML5 / CSS3


---

## ▶️ Como Executar

```bash
pip install -r requirements.txt
python app.py
```

Acesse:

```
http://127.0.0.1:5000
```

Usuário inicial:

```
admin / admin123
```

---

## 🎯 Objetivo do Projeto

Projeto educacional e profissional voltado para:

* Portfólio
* Estudos em Flask
* Sistemas administrativos
* Boas práticas de desenvolvimento web

---

## 👨‍💻 Autor

**Bruno Molina Souza**
Desenvolvedor Full Stack | 
Análise e Desenvolvimento de Sistemas
Projeto acadêmico e portfólio prático com Flask, banco de dados e deploy em nuvem.
---










