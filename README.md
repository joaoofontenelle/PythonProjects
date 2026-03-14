# 🐍 Projetos em Python  

Este repositório reúne diversos projetos e exercícios desenvolvidos durante meus estudos em Python 3, com foco em programação orientada a objetos (POO), manipulação de listas, loops, funções e boas práticas.  

Cada projeto representa um passo na jornada de aprendizado e serve como base para estudo, revisão ou futuras melhorias.  

---

## 📂 Projetos e Algoritmos  

### 1. 🎬 Gestão de Clientes e Planos de Streaming  
Arquivo: `clientes.py`  

- Classe `Clientes` com atributos: nome, e-mail e plano.  
- Planos disponíveis: `Gold` e `Platinum`.  
- Funcionalidades:  
  - Alterar plano.  
  - Validar plano selecionado.  
  - Assistir a um filme (com restrição baseada no plano do cliente).  

➡️ Exemplo:  
```python
cliente1 = Clientes('João', 'joao@email.com', 'Platinum')
cliente1.mudar_plano('Gold')

2. 🏪 Sistema de Controle de Estoque
Arquivo: estoque.py

Menu interativo via console com as opções:

Adicionar produto ao estoque

Verificar estoque

Remover produto do estoque (parcial ou total)

Sair do sistema

Estrutura de dados: lista de dicionários ({'Produto': nome, 'Quantidade': valor})

Uso de loops, validações e tratamento de erros.

3. 👨‍💼 Sistema de Registro e Gestão de Funcionários
Arquivo: funcionarios.py

Funções para:

Cadastrar novos funcionários (com dados como CPF, RG, endereço, cargo, salário, etc.).

Listar funcionários ativos.

Atualizar informações de funcionários.

Bloquear e desbloquear funcionários.

Destaques:

Funções auxiliares para formatação de CPF, RGs e datas.

Controle de status (Ativo/Inativo) para funcionários.

Fortes validações de entrada de usuário.

🛠️ Tecnologias Utilizadas
Python 3.x

Bibliotecas nativas: time, os

▶️ Como Executar
Clone o repositório:

Bash
git clone [https://github.com/joaoofontenelle/PythonProjects.git](https://github.com/joaoofontenelle/PythonProjects.git)
Entre na pasta do projeto:

Bash
cd PythonProjects
Execute qualquer script:

Bash
python nome_do_arquivo.py
🎯 Objetivo
Este repositório visa:

Consolidar conhecimentos adquiridos durante os estudos de Python.

Reunir projetos práticos que simulam sistemas do mundo real.

Servir como portfólio de aprendizado e prática de programação.

👨‍💻 Autor
Desenvolvido por João Victório Dos Santos Fontenelle 📧 Contato: joaofontenelle12570@gmail.com
cliente1.ver_filme('Star Wars', 'Platinum')
