# Meu Projeto de Portfólio 🚀

🛠️ Acompanhe comigo a minha evolução em **Python** desde o início do curso. 

---
  
## 📚 O que eu aprendi
Durante o desenvolvimento deste projeto, aprendi a:
- Criar um repositório no GitHub e organizar a estrutura.
- Trabalhar com versionamento de código.
- Utilizar PyCharm e IDLE
- Escrever um README.md claro e objetivo.

---

## 📂 Projetos

### 🐍 Projeto 1: Olá, Mundo!
Objetivo: Fazer o meu primeiro programa em Python.

📄 **Arquivo:**: [Olá, Mundo.py](https://github.com/user-attachments/files/21978398/001.-.Ola.Mundo.py) 

```python
print("Olá, mundo!")

```

### 🐍 Projeto 2: Qual é seu nome?
Objetivo: Fazer um programa que lê o nome do usuário e envia uma saldação.


📄 **Arquivo:**: [Qual é seu nome.py](https://github.com/user-attachments/files/21978408/002.-.Qual.seu.nome.py)

```python
pessoa=input('Digite seu nome:')
print('É um prazer te conhecer,',pessoa,'!')

```

---

### 🐍 Projeto 3: Primeira conta de adição.
Objetivo: Fazer o primeiro programa de soma em Python.

📄 **Arquivo:** [Primeiro conta de adição.py](https://github.com/user-attachments/files/21978449/Aula06.py)

```python
n1 = int(input('Digite um valor: '))
n2 = int(input('Digite outro valor: '))
s = n1 + n2
print(f'A soma de {n1} e {n2} vale {s}')

```

---

### 🐍 Projeto 4: Primeira calculadora.
Objetivo: Fazer minha primeira calculadora.

📄 **Arquivo:** [Primeira Calculadora.py](https://github.com/user-attachments/files/21978421/Desafio003.-.Primeira.Calculadora.py)

```python

print("=== Calculadora ===")
print("1 - Soma")
print("2 - Subtração")
print("3 - Multiplicação")
print("4 - Divisão")

op = int(input("Escolha a operação (1-4): "))

n1 = float(input("Digite o primeiro número: "))
n2 = float(input("Digite o segundo número: "))

if op == 1:
    print("Resultado:", n1 + n2)
elif op == 2:
    print("Resultado:", n1 - n2)
elif op == 3:
    print("Resultado:", n1 * n2)
elif op == 4:
    if n2 != 0:
        print("Resultado:", n1 / n2)
    else:
        print("Erro: divisão por zero!")
else:
    print("Operação inválida")

```

---

### 🐍 Projeto 5: Calculadora simples com interação (Botões, simbolos e que abra uma aplicação)
Objetivo: Fazer uma calculadora simples, porém em uma janela e mais interativa.

📄 **Arquivo:** [Calculadora com layout.py](https://github.com/user-attachments/files/21978491/Calculadora.Simples.-.Chat.py)

```python

import tkinter as tk

# Função para calcular
def calcular():
    try:
        resultado = eval(entrada.get())  # eval avalia a expressão (ex: "2+3*5")
        label_resultado.config(text="Resultado: " + str(resultado))
    except:
        label_resultado.config(text="Erro!")

# Criar janela
janela = tk.Tk()
janela.title("Calculadora")

# Campo de entrada
entrada = tk.Entry(janela, width=20, font=("Arial", 14))
entrada.pack(pady=10)

# Botão de calcular
botao = tk.Button(janela, text="Calcular", command=calcular)
botao.pack()

# Onde aparece o resultado
label_resultado = tk.Label(janela, text="Resultado: ")
label_resultado.pack(pady=10)

# Rodar a janela
janela.mainloop()

```

---

## ✨ Próximos Passos
- Adicionar novos projetos.
- Melhorar a documentação.
- Testar bibliotecas novas em Python.
