
# 🚀 Desafios em Python com GitHub Copilot & Codespaces

Este repositório contém a resolução de três desafios práticos propostos pela plataforma [DIO](https://www.dio.me/), utilizando **GitHub Codespaces** e **GitHub Copilot** para resolver algoritmos em Python.

---

## 🧰 Tecnologias Utilizadas

- ✅ Python 3.12
- ✅ Git e GitHub
- ✅ GitHub Codespaces
- ✅ GitHub Copilot
- ✅ Visual Studio Code (web)

---

## 📂 Estrutura do Projeto

```
📦 desafio-algoritmos-python
├── desafio_1.py                 # Concatenando dados
├── desafio_2.py                 # Repetindo textos
├── desafio_3.py                 # Operações matemáticas simples
├── README.md                    # Documentação do projeto
└── LICENSE                      # Licença MIT
```

---

## ✅ Desafios Resolvidos

### 1️⃣ Desafio: Concatenando Dados 🧩

📄 **Descrição:**  
Solicitar ao usuário dois dados diferentes e concatená-los em uma única string.

📌 **Conceitos aplicados:**
- Manipulação de `strings`
- Entrada com `input()`
- Concatenação com `+`
- Sugestões do Copilot

📁 Arquivo: [`desafio_1.py`](./desafio_1.py)

```python
nome = input("Digite seu primeiro nome: ")
sobrenome = input("Digite seu sobrenome: ")
print("Nome completo:", nome + " " + sobrenome)
```

---

### 2️⃣ Desafio: Repetindo Textos ✏️

📄 **Descrição:**  
Solicitar uma string e um número inteiro do usuário. Exibir a string repetida o número de vezes informado.

📌 **Conceitos aplicados:**
- Manipulação de `strings`
- Conversão com `int()`
- Operador de repetição (`*`)
- Entrada de dados
- Sugestões do Copilot

📁 Arquivo: [`desafio_2.py`](./desafio_2.py)

```python
texto = input("Digite uma palavra ou frase: ")
repeticoes = int(input("Quantas vezes deseja repetir? "))
print("Resultado:", texto * repeticoes)
```

---

### 3️⃣ Desafio: Operações Matemáticas Simples 🔣

📄 **Descrição:**  
Solicitar dois números e uma operação matemática básica (+, -, *, /), e mostrar o resultado.

📌 **Conceitos aplicados:**
- Entrada de dados com `float()`
- Operadores matemáticos
- Condicionais `if/elif/else`
- Verificação de divisão por zero
- Sugestões do Copilot

📁 Arquivo: [`desafio_3.py`](./desafio_3.py)

```python
num1 = float(input("Digite o primeiro número: "))
num2 = float(input("Digite o segundo número: "))
operacao = input("Digite a operação (+, -, *, /): ")

if operacao == '+':
    resultado = num1 + num2
elif operacao == '-':
    resultado = num1 - num2
elif operacao == '*':
    resultado = num1 * num2
elif operacao == '/':
    if num2 != 0:
        resultado = num1 / num2
    else:
        resultado = "Erro: divisão por zero!"
else:
    resultado = "Operação inválida!"

print("Resultado:", resultado)
```

---

## 🧠 Aprendizados

Durante esse projeto, foram praticados:
- Criação e uso de ambientes no GitHub Codespaces
- Sugestões inteligentes com GitHub Copilot
- Lógica de programação com Python
- Estruturação de repositório GitHub com boas práticas

---

## ✍️ Autor

**Bruno Mateus Barbosa Santos**  
📧 bmbsdeveloper5207418@gmail.com  
🔗 [GitHub](https://github.com/BrunoMateus8817)

---

## 📄 Licença

Distribuído sob a licença MIT. Veja `LICENSE` para mais informações.
