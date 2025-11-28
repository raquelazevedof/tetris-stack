# Tetris Stack 🎮🧱

Sistema em C que simula o controle de pecas do jogo Tetris Stack utilizando **fila** e **pilha**.

---

## 🔧 Recursos

- 🌀 **Fila circular**: controla as pecas futuras  
- 📦 **Pilha**: armazena pecas reservadas  
- 🔄 **Integracao fila <-> pilha**
  - Reservar peca  
  - Recuperar peca  
  - Trocar topo com frente  
  - Transferir N pecas  
  - Trocar pilha com primeiros M da fila
 
🎯 Objetivo

Demonstrar fila + pilha + integracao usando C, structs, arrays e logica de jogo.

---

## ▶️ Compilar

```sh
gcc -std=c11 -Wall -Wextra -o tetris_stack tetris_stack.c
