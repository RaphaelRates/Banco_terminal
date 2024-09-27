# Conta de Banco por Terminal

Este é um projeto de um sistema bancário básico, desenvolvido em Python. O sistema permite a criação de contas, depósitos, retiradas e consulta de saldo de maneira simples e intuitiva.

## Funcionalidades

O programa oferece as seguintes operações:

1. **Criar Nova Conta**: Permite criar uma nova conta com saldo inicial de R$0.00.
2. **Depositar**: Deposita uma quantia especificada em uma conta existente.
3. **Retirar**: Retira uma quantia de uma conta existente, desde que haja saldo suficiente.
4. **Verificar Saldo**: Mostra o saldo atual da conta.
5. **Sair**: Encerra o programa.

### Exemplo de Execução

#### 1. Criar Nova Conta
Escolha uma opção:

Criar nova conta
Depositar
Retirar
Verificar saldo
Sair 1 Digite o nome do titular da conta: João
markdown
Copiar código
**Saída**: `Conta criada para João.`

#### 2. Depositar
Escolha uma opção:

Criar nova conta
Depositar
Retirar
Verificar saldo
Sair 2 Digite o nome do titular da conta: João Digite a quantia a ser depositada: 100.00
markdown
Copiar código
**Saída**: `Depósito de R$100.00 realizado com sucesso.`

#### 3. Retirar
Escolha uma opção:

Criar nova conta
Depositar
Retirar
Verificar saldo
Sair 3 Digite o nome do titular da conta: João Digite a quantia a ser retirada: 50.00
markdown
Copiar código
**Saída**: `Saque de R$50.00 realizado com sucesso.`

#### 4. Verificar Saldo
Escolha uma opção:

Criar nova conta
Depositar
Retirar
Verificar saldo
Sair 4 Digite o nome do titular da conta: João
markdown
Copiar código
**Saída**: `Saldo atual: R$50.00`

#### 5. Sair
Escolha uma opção:

Criar nova conta
Depositar
Retirar
Verificar saldo
Sair 5
markdown
Copiar código
**Saída**: `Obrigado por usar o sistema bancário.`

## Estrutura do Projeto

- Entrada e saída de dados utilizando `input()` e `print()`.
- Estruturas condicionais (`if`, `elif`, `else`) para processar a escolha do usuário.
- Utilização de estruturas de repetição (`while`) para manter o programa em execução até que o usuário escolha a opção de sair.
- Dicionários são usados para armazenar as contas e seus respectivos saldos.

## Como Executar

1. Clone este repositório.
2. Execute o arquivo `banco.py` no seu terminal:
   ```bash
   python banco.py
