# 📚 Sistema de Cadastro de Alunos

Este é um programa simples feito em Python para **cadastrar alunos**, **listar cadastros** e **ver estatísticas** com base nas notas e idades dos alunos.

---

## 🚀 Funcionalidades

O sistema funciona por meio de um menu interativo que oferece as seguintes opções:

### 1️⃣ Cadastrar um novo aluno
- Solicita o nome e a idade do aluno.
- Recebe 3 notas (entre 0 e 10), com validação.
- Armazena os dados em uma lista de dicionários.

### 2️⃣ Listar alunos cadastrados
- Exibe o nome, idade e notas de cada aluno cadastrado.
- Se não houver alunos cadastrados, exibe uma mensagem de aviso.

### 3️⃣ Ver estatísticas
- Mostra a **média de idade** dos alunos.
- Informa qual aluno teve a **maior média de notas**.
- Conta quantos alunos estão **aprovados** (média ≥ 7).

### 4️⃣ Sair do programa
- Encerra a execução do programa com uma mensagem de despedida.

---

## 🛠️ Tecnologias utilizadas

- Python 3
- Estruturas de dados (`list`, `dict`)
- Estruturas de repetição (`while`, `for`)
- Condicionais (`if`, `match-case`)
- Validação de entrada

---

## 💡 Exemplo de uso

```bash
-----------MENU-----------
1 - Cadastrar um novo aluno
2 - listar alunos cadastrados
3 - Ver estatísticas
4 - Sair do programa
Escolha uma opção: 1
Escreva o novo aluno: Ana
Escreva a idade do aluno: 16
insira as notas de 0 a 10: 8
insira as notas de 0 a 10: 7
insira as notas de 0 a 10: 9
Aluno cadastrado!
