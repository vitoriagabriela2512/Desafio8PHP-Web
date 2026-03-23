# 📌 Sistema de Login + Tema com Cookies

## 🧾 Descrição

Este projeto contém dois exemplos práticos em PHP:

- 🔐 Sistema de Login com **Session e Cookie**
- 🎨 Preferência de Tema (Claro/Escuro) com **Cookies**

---

# 📁 Estrutura

## 🔐 Login

exemplo1/
│
├── index.php
├── validar.php
├── dashboard.php
└── sair.php

---

## 🎨 Tema

tema-com-cookies/
│
├── index.php
├── set_tema.php
└── style.css

---

# 🚀 Como executar

1. Colocar o projeto em:
C:\xampp\htdocs\

2. Iniciar o XAMPP (Apache)

3. Acessar:
http://localhost/nome-da-pasta

---

# 🔐 Exemplo 1: Sistema de Login

## ✔ Funcionalidades

- Login com usuário e senha
- Proteção de página com session
- Cookie "lembrar-me"
- Logout

---

## 🔑 Dados para login

Usuário: vitoria  
Senha: 1234  

---

## ⚙️ Funcionamento

### index.php
- Formulário de login
- Preenche usuário via cookie
- Exibe erro com session

### validar.php
- Valida login
- Cria session
- Salva cookie se marcado

### dashboard.php
- Página protegida
- Exibe usuário logado

### sair.php
- Destroi session
- Redireciona

---

# 🎨 Exemplo 2: Tema com Cookies

## ✔ Funcionalidades

- Escolha entre tema claro ou escuro
- Salva preferência em cookie
- Carrega automaticamente o tema

---

## ⚙️ Funcionamento

### index.php
- Lê cookie "tema"
- Aplica classe no body

### set_tema.php
- Salva cookie do tema

### style.css
- Define estilos:
  - Claro
  - Escuro

---

# 🧠 Conceitos utilizados

- $_SESSION
- $_COOKIE
- setcookie()
- Estrutura PHP
- HTML + CSS

---

# ⚠️ Observações

- Não armazenar senha em cookie
- Sempre usar session_start()
- Usar htmlspecialchars() para segurança

---

# ✅ Conclusão

O projeto demonstra:

✔ Uso de Sessions para login  
✔ Uso de Cookies para preferências  
✔ Integração entre PHP, HTML e CSS  
✔ Estrutura básica de sistema web  

# Autor👩‍💻

Desenvolvido por Vitória Gabriela Fernandes da Luz

---
