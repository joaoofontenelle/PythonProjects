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
cliente1.ver_filme('Star Wars', 'Platinum')
