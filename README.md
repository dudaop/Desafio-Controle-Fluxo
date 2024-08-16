# 🚀 Desafio Controle de Fluxo
Este projeto é parte de um desafio de controle de fluxo em Java. O objetivo é implementar um sistema que receba dois números inteiros via terminal e realize interações baseadas nesses números. Além disso, o sistema deve tratar exceções customizadas para garantir que o segundo número seja sempre maior que o primeiro.

## 📋 Funcionalidades 
1. Entrada de Dados: O sistema solicita dois números inteiros ao usuário.
2. Controle de Fluxo: Realiza um loop for com base na diferença entre os dois números.
3. Exceção Customizada: Se o primeiro número for maior que o segundo, uma exceção ParametrosInvalidosException é lançada.

## 🛠️ Tecnologias Utilizadas
- Java: Linguagem principal usada para o desenvolvimento do projeto.
- Scanner: Para entrada de dados via terminal.
- Tratamento de Exceções: Utilização de try-catch para capturar e tratar exceções customizadas.

## 🚀 Como Executar
1. Certifique-se de ter o Java instalado no seu sistema.
2. Clone este repositório ou copie o código para sua máquina local.
3. Compile e execute o arquivo `ContaTerminal.java`.
4. Insira as informações solicitadas no terminal.
5. Utilize o menu de opções para realizar depósitos, saques, verificar o saldo ou sair do programa.
6. Veja a mensagem de confirmação com os dados da conta e o saldo atualizado após cada operação.

## 📄 Estrutura do Projeto
- ParametrosInvalidosException.java: Classe responsável por representar a exceção customizada.
- Contador.java: Classe principal onde a lógica do sistema é implementada.

## ⚠️ Regras de Negócio
O segundo número deve ser sempre maior que o primeiro. Caso contrário, o sistema lança uma exceção com a mensagem: "O segundo parâmetro deve ser maior que o primeiro".

## 🎯 Objetivo
Este projeto visa consolidar os conceitos de controle de fluxo, manipulação de exceções, e interação com o usuário via terminal em Java.

## Contribuição 🤝
Sinta-se à vontade para abrir issues e pull requests para melhorias.😄
