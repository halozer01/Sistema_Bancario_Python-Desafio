# Sistema Bancário em Python

Este projeto é um sistema bancário simples desenvolvido em Python, criado como parte de um desafio de programação. O objetivo do sistema é fornecer funcionalidades básicas de um banco, como depósitos, saques e exibição de extratos.

## Melhorias Aplicadas

1. **Modularização de Funções**:
   - As funcionalidades foram separadas em funções distintas (`depositar`, `sacar`, `exibir_extrato` e `menu`), o que melhora a organização e a clareza do código.

2. **Validações Simplificadas**:
   - As validações de entrada e condições de operação foram agrupadas dentro das funções apropriadas, reduzindo a repetição de código e facilitando a manutenção.

3. **Mensagens de Sucesso e Erro**:
   - Foram adicionadas mensagens de sucesso para operações válidas, além de mensagens de erro detalhadas para operações inválidas, melhorando a experiência do usuário.

4. **Estrutura Principal (`main`)**:
   - A estrutura principal do programa foi organizada na função `main()`, permitindo uma execução mais clara e controlada do fluxo do programa.

## Benefícios das Melhorias

- **Legibilidade**: A separação das funcionalidades em funções distintas torna o código mais fácil de ler e entender.
- **Manutenção**: Com validações centralizadas e funções modulares, fica mais simples realizar modificações e adições ao código.
- **Escalabilidade**: A organização do código facilita a adição de novas funcionalidades no futuro.
- **Reusabilidade**: As funções podem ser reutilizadas em diferentes partes do programa ou em outros projetos.
