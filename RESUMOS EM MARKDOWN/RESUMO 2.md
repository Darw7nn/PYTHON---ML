d# 🐍 Guia Rápido: Variáveis e Tipos Básicos em Python

Bem-vindo ao tutorial de **Variáveis e Tipos de Dados**! Este guia vai te ensinar os fundamentos absolutos da linguagem Python. Se você quer criar programas, analisar dados ou construir modelos de Inteligência Artificial, tudo começa por aqui! 🚀

---

## 📦 1. O que são Variáveis?

Pense nas variáveis como "etiquetas" que você cola em caixas para guardar informações na memória do computador. Em Python, tudo é tratado como um **objeto** (números, textos, etc.). Quando você cria uma variável, você está apontando para um objeto que tem um tipo e um valor.

```python
idade = 20
nome = "Ana"
altura = 1.65
```

---

## 🧬 2. Os Quatro Tipos de Dados Básicos

O Python possui tipagem dinâmica, o que significa que ele descobre sozinho que tipo de dado você está guardando. Os quatro mais importantes são:

* 🔢 **Inteiros (`int`):** Números sem casas decimais.
    * `quantidade = 10`
* 📏 **Ponto Flutuante (`float`):** Números com casas decimais (use sempre ponto `.` em vez de vírgula).
    * `preco = 19.90`
* 🔤 **Texto/Strings (`str`):** Letras, palavras e frases. Sempre entre aspas (simples ou duplas).
    * `mensagem = "Python é incrível"`
* ✅ **Booleanos (`bool`):** Valores lógicos: Verdadeiro (`True`) ou Falso (`False`). Note a letra maiúscula!
    * `aprovado = True`

---

## 🕵️‍♂️ 3. Descobrindo o Tipo com `type()`

Ficou na dúvida sobre qual é o tipo de dado de uma variável? Use a função mágica `type()`!

```python
idade = 20
print(type(idade)) # Saída: <class 'int'>

preco = 19.90
print(type(preco)) # Saída: <class 'float'>
```

---

## 🗣️ 4. Conversando com o Usuário e "Casting"

Você pode pedir para o usuário digitar informações usando o `input()`. 
**Atenção:** Tudo o que vem do `input()` chega como *Texto* (`str`). Se quiser fazer contas, precisa converter o tipo (processo chamado de **Casting**):

```python
# Recebendo texto
nome = input("Digite seu nome: ")

# Recebendo número e convertendo (Casting)
idade = int(input("Digite sua idade: "))
altura = float(input("Digite sua altura: "))
```

---

## 🧮 5. Operadores Matemáticos Básicos

O Python é uma calculadora superpoderosa. Aqui estão os operadores essenciais:

```python
a = 10
b = 3

print(a + b)  # Soma (13)
print(a * b)  # Multiplicação (30)
print(a ** b) # Exponenciação / Potência (10³ = 1000)
```

---

## 🌟 6. Boas Práticas (Como escrever código bonito)

Para ser um bom programador, siga estas regrinhas ao dar nomes às suas variáveis:
1.  **Seja claro:** Use `total_alunos` ao invés de apenas `t`.
2.  **Sem acentos ou espaços:** Use sublinhados (`_`).
3.  **Padrão snake_case:** Tudo em minúsculo, separado por sublinhado. Ex: `media_final = 8.2`.

---

## 💻 7. Mão na Massa: Código Completo (Exercícios Resolvidos)

Aqui estão exemplos práticos juntando entrada de dados, conversão, cálculos matemáticos e lógica booleana:

```python
# Exemplo 1: Coletando dados simples
nome = input("Digite seu nome: ")
idade = int(input("Digite sua idade: "))
print("O usuário tem", idade, "anos e se chama", nome)

# Exemplo 2: Somando dois números
num1 = int(input("Digite um numero: "))
num2 = int(input("Digite um numero: "))
print("A soma é:", num1 + num2)

# Exemplo 3: Calculando a média de 3 notas
med1 = int(input("Digite a primeira nota do aluno: "))
med2 = int(input("Digite a segunda nota do aluno: "))
med3 = int(input("Digite a terceira nota do aluno: "))
print("A média do aluno é:", (med1 + med2 + med3) / 3)

# Exemplo 4: Lógica de Aprovação (Booleano)
notaaluno = float(input("Digite a nota do aluno: "))
notamin = 7.0

# Verifica se a nota é maior ou igual à mínima
aprovado = notaaluno >= notamin 

# A letra 'f' antes das aspas formata o texto junto com a variável!
print(f"Aluno aprovado? {aprovado}") 
```

---
*Bons estudos e continue codando!* ☕👨‍💻👩‍💻
