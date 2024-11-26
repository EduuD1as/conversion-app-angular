# Aula 25-11 - App Conversão de moeda

## Avaliação

* Implemente para que o usuário possa fazer conversão de outras moedas (mínimo + 3 moedas);
* Descreva abaixo o seu entendimento acerca desta atividade, explorando as funcionalidades das classes que contruímos e os principais pontos da aplicação;

## Entrega

* Clone este repositório e faça o que se pede;
* Realize um commit das suas alterações no seu repositório;
* Envie o link do repositório na avaliação gerada no classroom;

## Descritivo do Aluno:

A atividade envolve expandir uma aplicação de conversão de moedas, permitindo que o usuário converta entre pelo menos 4 moedas diferentes.

### Funcionalidades das Classes:
Classe de Conversão: Calcula o valor convertido entre as moedas. Utiliza uma API de taxas de câmbio (Axios) para obter as taxas e fazer a conversão.

Interface de Usuário: Permite ao usuário a inserção das moedas de origem e destino e após a escolha da conversão ver o resultado.

API de Taxas de Câmbio: Integra a aplicação com uma API para obter as taxas de câmbio em tempo real, permitindo que as conversões sejam feitas de acordo com valores atualizados do mercado.

### Pontos Principais:
Atualização em Tempo Real: A API fornece as taxas de câmbio em tempo real para que as conversões sejam precisas.
Validação de Entradas: A aplicação valida entradas do usuário, como valores válidos e moedas selecionadas.
A aplicação permite conversões rápidas e precisas entre diferentes moedas, com uma interface amigável e integração com uma API externa.
