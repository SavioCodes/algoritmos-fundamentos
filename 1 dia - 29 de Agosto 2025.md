# Dia 1 — 29/08/2025

Hoje comecei oficialmente meus estudos de algoritmos e fundamentos de programação.  
Estou usando Windows e o Visual Studio Code (VS Code) como editor.  

A ideia é registrar tudo: o que estudei, o que aprendi, exemplos de código, erros que cometi e reflexões sobre o aprendizado.

---

## O que estudei hoje
- O que é um algoritmo  
- Variáveis (como guardar informações)  
- Condicionais (`if/else`)  
- Laços de repetição (`for`)  

---

## O que aprendi

### O que é um algoritmo
Um algoritmo é basicamente uma **receita de passos** para resolver um problema.  
Pode ser algo simples, tipo escovar os dentes:

1. Pegar a escova  
2. Passar pasta de dente  
3. Escovar  
4. Enxaguar  

Tudo isso é um algoritmo, só que para o dia a dia.

---

### Variáveis
Variáveis são como **caixinhas de memória**. Elas guardam informações que podemos usar depois.  
No Python, não preciso falar o tipo da variável, ele entende sozinho.  

```python
idade = 15      # número inteiro
nome = "Savio"  # texto (string)
maior = True    # verdadeiro ou falso
```

---

### Condicionais (`if/else`)
Servem para tomar decisões no código. Tipo “se isso, faça aquilo; senão, faça outra coisa”.  

```python
idade = 15

if idade >= 18:
    print("Maior de idade")
else:
    print("Menor de idade")
```

Se `idade >= 18` for verdadeiro, o Python executa o bloco do `if`.  
Se não for, ele executa o `else`.

---

### Laços de repetição (`for`)
O `for` serve para repetir algo várias vezes sem precisar escrever tudo de novo.  

```python
for i in range(5):
    print("Repetição número", i)
```

- `range(5)` gera os números de 0 até 4  
- `i` recebe cada número  
- O `print` roda 5 vezes, mudando o número a cada vez  

Saída no console:

```
Repetição número 0
Repetição número 1
Repetição número 2
Repetição número 3
Repetição número 4
```

---

## Erros que cometi
- Esqueci os dois pontos `:` no final do `if` → erro de sintaxe  
- Usei `range(1,5)` achando que incluía o 5 → na verdade só vai até 4  
- Esqueci de colocar `print()` com parênteses → obrigatório no Python 3  

Esses erros me ajudaram a prestar mais atenção nos detalhes.

---

## Testes extras
Brinquei com o `while`, mas ainda fiquei na dúvida sobre quando usar `for` ou `while`:  

```python
contador = 0
while contador < 5:
    print("Número:", contador)
    contador += 1
```

---

## Dúvidas que fiquei
- Quando é melhor usar `for` e quando usar `while`?  
- Como o Python decide o tipo da variável?  
- Há diferença de desempenho entre `if/else` e outros tipos de decisão?

---

## Reflexão do dia
Primeiro dia concluído 🚀  
Entendi bem os conceitos de **variáveis**, **if/else** e **laços de repetição**.  
Ainda é só o básico, mas já ajuda a organizar as ideias.  

Gostei de ver os erros acontecendo, porque eles me forçam a aprender de verdade.  

Próximo passo: praticar mais `while`, listas e começar a mexer com funções.
