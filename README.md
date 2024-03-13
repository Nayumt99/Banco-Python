# Sistema Bancário Simples em Python
Este é um sistema bancário simples implementado em Python que permite realizar operações básicas como depósito, saque e consultar extrato.

## Funcionalidades

1. Depósito:
Permite ao cliente realizar depósitos na conta.

2. Saque:
Permite ao cliente efetuar saques da conta, desde que haja saldo disponível.

3. Extrato:
Fornece ao cliente o saldo atual da conta.

##Uso

1. Criar uma Conta:
  ```bash
conta = ContaBancaria(saldo_inicial)
```
Cria uma conta bancária com um saldo inicial opcional.

2. Depósito:
```bash
conta.deposito(valor)
```
Realiza um depósito na conta.


3. Saque:
```bash
conta.saque(valor)
```
Efetua um saque da conta, desde que haja saldo suficiente.

4. Extrato:
```bash
conta.extrato()
```
Exibe o saldo atual da conta.

## Exemplo de Uso
```bash
# Criar conta com saldo inicial de R$1000
conta = ContaBancaria(1000)

# Realizar depósito de R$500
conta.deposito(500)
conta.extrato()

# Efetuar saque de R$200
conta.saque(200)
conta.extrato()
```

Este é um exemplo básico que pode ser expandido conforme necessário para atender a requisitos específicos ou adicionar mais funcionalidades ao sistema bancário. Certifique-se de considerar aspectos como tratamento de erros, validação de entradas e segurança, dependendo do contexto de uso.

