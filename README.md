# 💬 Mostrar uma Frase Usando Variáveis — Python

Um programa simples em **Python** que utiliza variáveis para armazenar o nome e a idade de uma pessoa e, em seguida, exibe essas informações em uma frase personalizada.

## 📌 Sobre o projeto

Este exercício demonstra como utilizar **variáveis dentro de uma string** através das **f-strings**.

O programa armazena o nome e a idade nas variáveis `nome` e `idade` e utiliza esses valores para montar uma frase automaticamente.

## 💻 Código

```python
nome = "Carlos"
idade = 28

# Exibindo a frase com f-string
print(f"Olá, meu nome é {nome} e eu tenho {idade} anos.")
```

## 🔎 Como funciona?

### 1. Criando as variáveis

```python
nome = "Carlos"
idade = 28
```

Aqui criamos duas variáveis para armazenar informações:

| Variável | Valor      | Tipo  |
| -------- | ---------- | ----- |
| `nome`   | `"Carlos"` | `str` |
| `idade`  | `28`       | `int` |

A variável `nome` armazena um texto, enquanto `idade` armazena um número inteiro.

### 2. Utilizando uma f-string

```python
print(f"Olá, meu nome é {nome} e eu tenho {idade} anos.")
```

O `f` antes das aspas transforma a string em uma **f-string**.

Isso permite colocar variáveis diretamente dentro do texto utilizando `{}`.

Por exemplo:

```python
{nome}
{idade}
```

Durante a execução, esses espaços são substituídos pelos valores armazenados nas variáveis.

## ▶️ Resultado

```text
Olá, meu nome é Carlos e eu tenho 28 anos.
```

## 📚 Conceitos aprendidos

| Conceito  | Descrição                                     |
| --------- | --------------------------------------------- |
| Variáveis | Armazenam informações                         |
| `str`     | Representa textos                             |
| `int`     | Representa números inteiros                   |
| `print()` | Exibe informações no terminal                 |
| f-string  | Permite inserir variáveis dentro de strings   |
| `{}`      | Define onde o valor da variável será inserido |

## 🎯 Objetivo

Aprender a utilizar **variáveis dentro de frases**, utilizando f-strings para criar textos dinâmicos e personalizados.

Este conceito será muito utilizado em programas que precisam apresentar informações armazenadas em variáveis.

---

🐍 **Python — Fundamentos**
