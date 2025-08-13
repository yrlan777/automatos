# 🦟 Simulação da Disseminação da Dengue com Autômato Celular

Este projeto implementa um **autômato celular em Python** para simular a disseminação da dengue em uma população fictícia, representada por uma grade bidimensional.  
O modelo considera a propagação por meio de mosquitos *Aedes aegypti*, permitindo observar a evolução da doença ao longo do tempo.

---

## 📜 Descrição

O objetivo desta simulação é estudar, de forma simplificada, como a dengue pode se espalhar em uma comunidade e como medidas de controle podem influenciar essa dinâmica.  
O sistema utiliza uma matriz para representar indivíduos e focos de mosquito, atualizando seu estado a cada passo temporal segundo regras pré-definidas.

---

## 🧪 Estados do Modelo

Cada célula da grade pode assumir um dos seguintes estados:

- **0** → Pessoa saudável 🟩
- **1** → Pessoa infectada 🟥
- **2** → Pessoa recuperada/imune 🟦
- **3** → Foco de mosquito (Aedes aegypti) 🟨

---

## ⚙️ Funcionamento

A cada iteração:

1. Mosquitos infectam pessoas saudáveis adjacentes com uma certa **probabilidade de infecção**.
2. Pessoas infectadas tornam-se recuperadas após um número fixo de iterações.
3. Novos focos de mosquito podem surgir aleatoriamente na grade.

---

## 📈 Exemplo de Simulação

A simulação gera uma animação em tempo real mostrando a evolução da infecção na grade:

![Exemplo de Simulação](exemplo_simulacao.gif)

---

## 📂 Estrutura do Projeto

