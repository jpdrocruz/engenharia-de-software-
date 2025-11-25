Sistema de Gráfica — Controle de Pedidos em Python com Observer, Factory Method e Polimorfismo

Este projeto é um sistema de gerenciamento de pedidos para gráfica, desenvolvido em Python, utilizando padrões modernos de projeto. Ele oferece um fluxo simples e eficiente para criação e acompanhamento de pedidos.

Funcionalidades do Sistema

Criar pedidos com base no tamanho em m²

Calcular automaticamente o preço de acordo com o material selecionado

Notificar o cliente sempre que houver alterações importantes

Atualizar o status do pedido (em produção, finalizado etc.)

Enviar mensagens para o cliente

Visualizar o painel de produção com todos os pedidos e seus respectivos status

Interface em menu de terminal para fácil navegação

Tecnologias Utilizadas

Python

Padrões de Projeto Modernos

Observer (Observador)

Factory Method (Método de Fábrica)

Polimorfismo

Padrões de Projeto Implementados

🔹 Padrão Observer

Utilizado para permitir que o cliente receba notificações sempre que:

O status do pedido for alterado

Uma mensagem ou aviso for enviado

Classes aplicadas:

Cliente (Observador)

🔹 Factory Method

Utilizado para criar pedidos de forma padronizada, facilitando a expansão do sistema.

Classe aplicada:

Pedido (criação por fábrica)

🔹 Polimorfismo

Usado para permitir que diferentes tipos de pedidos ou materiais tenham cálculos específicos sem alterar o fluxo principal do código.
