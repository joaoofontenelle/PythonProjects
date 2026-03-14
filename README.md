# 🐍 Projetos em Python  

Este repositório reúne diversos projetos e exercícios desenvolvidos durante meus estudos em Python 3, com foco em programação orientada a objetos, manipulação de listas, loops, funções e boas práticas.

Cada projeto representa uma etapa da jornada de aprendizado e pode servir como base para estudo, revisão ou futuras melhorias.

---

## 📂 Projetos e Algoritmos  

### 1. 🎬 Gerenciamento de Clientes e Planos de Streaming  

Arquivo: `clientes.py`

- Classe `Clientes` com atributos nome, email e plano.
- Planos disponíveis: `Gold` e `Platinum`.
- Funcionalidades:
  - Alterar plano.
  - Validar o plano selecionado.
  - Assistir a um filme (restrito de acordo com o plano do cliente).

➡️ Exemplo:

```python
cliente1 = Clientes('João', 'joao@email.com', 'Platinum')

cliente1.mudar_plano('Gold')
cliente1.ver_filme('Star Wars', 'Platinum')
```

---

### 2. 🏪 Sistema de Controle de Estoque

Arquivo: `estoque.py`

- Menu interativo no console com opções:

  1. Adicionar produto ao estoque
  2. Consultar estoque
  3. Remover produto do estoque (parcial ou total)
  4. Sair do sistema

- Estrutura de dados: lista de dicionários (`{'Produto': nome, 'Quantidade': valor}`)

- Uso de **loops, validações e tratamento de erros**.

---

### 3. 👨‍💼 Sistema de Cadastro e Gestão de Funcionários

Arquivo: `funcionarios.py`

- Funções para:

  - Cadastrar novos funcionários (com dados como CPF, RG, endereço, cargo, salário, etc.).
  - Listar funcionários ativos.
  - Atualizar informações dos funcionários.
  - Bloquear e desbloquear funcionários.

- Destaques:

  - Funções auxiliares para **formatação de CPF, RG e datas**.
  - **Controle de status (Ativo/Inativo)** dos funcionários.
  - Validações robustas de entrada de dados do usuário.

---

## 🛠️ Tecnologias Utilizadas

- **Python 3.x**
- Bibliotecas nativas: `time`, `os`

---

## ▶️ Como Executar

1. Clone o repositório:

```bash
git clone https://github.com/joaoofontenelle/PythonProjects.git
```

2. Entre na pasta do projeto:

```bash
cd PythonProjects
```

3. Execute qualquer script:

```bash
python nome_do_arquivo.py
```

---

## 🎯 Objetivo

Este repositório tem como objetivo:

- Consolidar o conhecimento adquirido durante os estudos em Python.
- Reunir projetos práticos que simulam **sistemas do mundo real**.
- Servir como portfólio de aprendizado e prática de programação.

---

## 👨‍💻 Autor

Desenvolvido por **João Victório Dos Santos Fontenelle**

📧 Contato: joaofontenelle12570@gmail.com

---
