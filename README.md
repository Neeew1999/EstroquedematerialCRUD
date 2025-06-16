# Sistema de Controle de Estoque - CRUD Java Desktop

## 🎯 Objetivo

Este projeto foi desenvolvido como parte da disciplina de *Análise e Projeto Orientado a Objetos (APOO)* do curso de *Análise e Desenvolvimento de Sistemas. O objetivo é aplicar os conceitos de **programação orientada a objetos* e *persistência de dados* utilizando um sistema CRUD funcional, com *interface gráfica em Java (Swing)* e integração com banco de dados *SQLite*.

---

## 💻 Tecnologias Utilizadas

- Java SE (versão 8+)
- Swing (Interface Gráfica)
- JDBC (Java Database Connectivity)
- SQLite (Banco de Dados Relacional)
- sqlite-jdbc (Driver JDBC)

---

## ⚙ Funcionalidades

O sistema permite o gerenciamento de produtos com as seguintes operações:

- ✅ Cadastro de produtos
- 📄 Listagem de produtos
- ✏ Edição de informações
- ❌ Exclusão de produtos

---

## 🗃 Estrutura do Projeto
SistemaControleEstoqueAtualizado/
├── Main.java → Classe principal que inicia o sistema
├── Produto.java → Classe de modelo (entidade Produto)
├── ProdutoDAO.java → Acesso ao banco de dados (CRUD com JDBC)
├── ProdutoForm.java → Interface gráfica com Swing
├── estoque.db → Banco de dados SQLite com tabela 'produtos'
├── sqlite-jdbc-3.36.0.3.jar → Driver JDBC necessário para conexão

---

## 🧪 Como Executar

1. *Tenha o Java JDK instalado* (verifique com java -version)
2. Baixe o driver SQLite JDBC:  
   [sqlite-jdbc-3.36.0.3.jar](https://repo1.maven.org/maven2/org/xerial/sqlite-jdbc/3.36.0.3/sqlite-jdbc-3.36.0.3.jar)
3. Coloque esse .jar dentro da pasta do projeto.
4. Compile os arquivos:
   ```bash
   javac -cp ".;sqlite-jdbc-3.36.0.3.jar" *.java
   java -cp ".;sqlite-jdbc-3.36.0.3.jar" Main

 ## 📝 Instalação e Configuração

    Não é necessário instalar o banco: o arquivo estoque.db já está pronto.

    O driver SQLite (sqlite-jdbc-3.36.0.3.jar) deve estar na mesma pasta do projeto.

    O projeto pode ser rodado via terminal ou IDE como NetBeans ou IntelliJ (adicionando o .jar ao classpath).

  