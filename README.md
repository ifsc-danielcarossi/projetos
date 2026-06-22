````markdown
# 🛍️ Loja Pedro

Sistema web de gerenciamento de loja desenvolvido em **PHP**, **MySQL** e **Bootstrap**, permitindo o cadastro e gerenciamento de clientes, produtos, categorias, vendedores, vendas e avaliações.

## 📋 Sobre o Projeto

O Loja Pedro é uma aplicação web para fins educacionais que demonstra a implementação de operações CRUD (Create, Read, Update e Delete) utilizando PHP e banco de dados MySQL.

O sistema possui uma interface administrativa que permite acompanhar informações gerais da loja por meio de um painel com indicadores e módulos de gerenciamento.

## 🚀 Funcionalidades

### 📦 Produtos
- Listagem de produtos
- Consulta de produtos cadastrados

### 🏷️ Categorias
- Cadastro de categorias
- Gerenciamento de categorias

### 👥 Clientes
- Cadastro de clientes
- Edição de clientes
- Exclusão de clientes
- Consulta de clientes

### 🧑‍💼 Vendedores
- Gerenciamento de vendedores
- Consulta de vendedores

### 💰 Vendas
- Registro de vendas
- Consulta de vendas

### ⭐ Avaliações
- Registro de avaliações de atendimento
- Controle de notas e comentários dos clientes

### 📊 Dashboard
- Total de clientes
- Total de produtos
- Total de vendas
- Total de vendedores
- Total de categorias
- Total de avaliações

---

## 🛠️ Tecnologias Utilizadas

- PHP
- MySQL / MariaDB
- HTML5
- CSS3
- Bootstrap 5
- JavaScript

---

## 📂 Estrutura do Projeto

```text
LojaPedro/
│
├── avaliacao/
├── categoria/
├── cliente/
├── conexaoBD/
│   └── db.php
├── produto/
├── venda/
├── vendedor/
├── bootstrap/
│   ├── css.css
│   ├── pricing.css
│   └── imagens/
├── sql/
│   └── Banco_lojapedro.sql
└── index.php
````

---

## ⚙️ Instalação

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/LojaPedro.git
```

### 2. Copie o projeto para o servidor web

Exemplo utilizando XAMPP:

```text
xampp/htdocs/LojaPedro
```

### 3. Crie o banco de dados

No MySQL, crie um banco chamado:

```sql
CREATE DATABASE lojapedro;
```

### 4. Importe o script SQL

Importe o arquivo:

```text
sql/Banco_lojapedro.sql
```

### 5. Configure a conexão

Arquivo:

```php
conexaoBD/db.php
```

Configuração padrão:

```php
$conn = mysqli_connect(
    "localhost",
    "root",
    "",
    "lojapedro"
);
```

Altere conforme as credenciais do seu ambiente.

### 6. Execute o sistema

Acesse:

```text
http://localhost/LojaPedro
```

---

## 🗄️ Banco de Dados

O sistema utiliza o banco de dados **lojapedro**, contendo tabelas como:

* cliente
* produto
* categoria
* vendedor
* venda
* avaliacao
* cidade
* estado

---

## 🎯 Objetivo Educacional

Este projeto foi desenvolvido com foco em aprendizagem dos seguintes conceitos:

* Programação Web com PHP
* Integração PHP + MySQL
* Estruturação de CRUDs
* Organização de projetos web
* Utilização de Bootstrap para interfaces responsivas
* Consultas SQL e modelagem de banco de dados

---

## 📸 Telas do Sistema

Sugestão:

* Dashboard
* Cadastro de Clientes
* Cadastro de Categorias
* Controle de Vendas
* Avaliações

*(Adicionar capturas de tela na pasta `/docs/images` e referenciá-las aqui.)*

---

## 👨‍💻 Autor

Projeto desenvolvido para fins acadêmicos e de aprendizado em desenvolvimento web utilizando PHP e MySQL.

---

## 📄 Licença

Este projeto está disponível para uso educacional e acadêmico.

```

Este README já está no padrão utilizado em projetos de portfólio no GitHub e pode ser copiado diretamente para um arquivo `README.md`.
```
