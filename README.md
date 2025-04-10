# Projeto Pizzaria Mobile

## Descrição

Este projeto está em desenvolvimento, é um aplicativo móvel para gerenciamento de pedidos em uma pizzaria. O objetivo é facilitar a experiência do garçom e do cliente, permitindo que os pedidos sejam feitos diretamente da mesa.

## Funcionalidades

- **Criação de Pedidos**: O garçom pode abrir um pedido diretamente na mesa.
- **Alterações no Pedido**: Possibilidade de fazer alterações no pedido antes da finalização.
- **Finalização de Pedidos**: Após a finalização, o pedido é enviado para a cozinha e notificado ao cliente na mesa.

## Tecnologia

- **Mobile**: [React native, Scss e token JWT.]

## Versão do Sistema Web

Este projeto será integrado com a versão do sistema web, onde será possível gerenciar os pedidos realizados pelo aplicativo.

## Justificativa de paradigmas 

Escolhemos o paradigma Orientado a Objetos porque ele permite organizar melhor o sistema da pizzaria, representando pedidos, produtos e usuários de forma clara com classes. Ele facilita a reutilização de código, garante mais segurança no controle de acessos e torna o sistema mais fácil de manter e expandir no futuro, mesmo com poucos recursos.

## Como executar o sistema 

Backend
Acesse a pasta do backend pelo terminal e execute o seguinte comando para subir o servidor em ambiente de desenvolvimento:

"npm run dev"

Mobile (React Native com Expo)
Em outro terminal, navegue até a pasta do app mobile e inicie o Expo com:

"npx expo start"

Isso vai abrir o Metro Bundler no prompt do comando, e você pode rodar o app no emulador, no dispositivo físico (via QR Code com o app Expo Go) ou em um simulador.
