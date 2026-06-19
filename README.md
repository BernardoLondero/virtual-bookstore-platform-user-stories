# Bookstore Platform - Engenharia de Requisitos e Modelagem BPMN

Este repositório contém o mapeamento de processos de negócio e o levantamento de requisitos para o desenvolvimento de uma plataforma de e-commerce e gestão de uma livraria digital.

## Objetivo do Projeto
O objetivo deste trabalho foi estruturar a visão completa do sistema: mapeando o fluxo logístico e de vendas de ponta a ponta, e traduzindo essas necessidades de negócio em requisitos ágeis (Product Backlog).

## 1. Modelagem de Processos (BPMN 2.0)
O fluxo do sistema foi desenhado utilizando o software Camunda, dividindo as responsabilidades nos seguintes atores (Pools/Lanes):
* Cliente: Jornada de navegação, seleção de livros e finalização de pedido.
* Sistema (Livraria Virtual): Regras automatizadas (validação de promoções, cálculo de frete, verificação e baixa de estoque).
* Sistemas Externos e Gerência: Integrações com operadoras de cartão, reposição de estoque com editoras e fluxos estratégicos de relatórios.
* Arquivos: O diagrama visual encontra-se no arquivo `diagrama-processo-vendas.png` e o código fonte importável no arquivo `fluxo-vendas-ecommerce.bpmn`.

## 2. Levantamento de Requisitos (User Stories)
* Redação: Criação de histórias de usuário cobrindo funcionalidades mapeadas no BPMN (como automação de frete e integrações).
* Gestão de Perfis: Categorização de requisitos baseados nas permissões de Clientes, Gerentes e Administradores do Sistema.
* Organização do Backlog: Estruturação visual das tarefas e simulação de Sprints utilizando um quadro Kanban.

## Visualização do Quadro Ágil
O fluxo de desenvolvimento e o backlog podem ser acompanhados diretamente na aba de projetos:

[Clique aqui para acessar o Quadro Kanban do Projeto](https://github.com/users/BernardoLondero/projects/1)
