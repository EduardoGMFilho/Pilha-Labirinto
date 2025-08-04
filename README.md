# Pilha-Labirinto

# 🔍 Projeto Labirinto com Backtracking em Python

Este projeto implementa uma solução para o clássico **Problema do Labirinto**, onde um jogador deve encontrar um **prêmio escondido** navegando por um labirinto 2D gerado a partir de um arquivo.

O foco aqui é a **implementação do algoritmo de backtracking com uso de pilha**, tudo visualizado via terminal (ou opcionalmente com Pygame, se não estiver no Colab).

---

## 📌 Objetivos

- Carregar labirintos a partir de arquivos `.txt` com matrizes binárias.
- Posicionar o jogador e o prêmio aleatoriamente em locais livres.
- Resolver o labirinto utilizando **backtracking com pilha (LIFO)**.
- Mostrar a movimentação do jogador até o prêmio.

---

## 🧠 Algoritmo Utilizado

Utilizamos uma pilha para armazenar os caminhos possíveis do jogador. A cada passo, a posição atual é explorada, e suas casas vizinhas (norte, sul, leste e oeste) são inseridas na pilha se forem acessíveis.

Este é um ótimo exemplo de aplicação prática de **estruturas de dados** e **algoritmos de busca**.

