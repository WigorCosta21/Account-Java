# Sistema de Cadastro de Conta Bancária

Este projeto implementa um sistema simples para o cadastro e gerenciamento de contas bancárias. O sistema permite a criação de uma conta, depósitos, saques e a atualização do nome do titular. O saldo da conta é gerido com segurança, evitando alterações não autorizadas.

## Funcionalidades

- **Cadastro de Conta**: Permite criar uma nova conta informando o número da conta, nome do titular e, opcionalmente, um valor de depósito inicial.
- **Depósito**: Permite adicionar valores à conta.
- **Saque**: Permite retirar valores da conta, com a aplicação de uma taxa fixa de $5,00 por saque.
- **Atualização do Titular**: O nome do titular da conta pode ser alterado a qualquer momento.

## Regras de Negócio

- O número da conta é único e não pode ser alterado após a criação da conta.
- O saldo da conta só pode ser alterado através de depósitos e saques.
- A conta pode ter saldo negativo caso o saque e a taxa excedam o saldo disponível.

## Estrutura do Código

O código é dividido em duas classes principais:

1. **`Account`**: Representa a conta bancária, com os métodos para realizar operações de depósito, saque e atualização de informações.
2. **`Main`**: Classe responsável pela interação com o usuário, permitindo a entrada de dados e exibindo informações sobre a conta.

## Dependências

- Java Development Kit (JDK) 8 ou superior.
- Nenhuma dependência externa adicional é necessária.
