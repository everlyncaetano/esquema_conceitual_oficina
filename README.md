# Esquema Conceitual - Sistema de Gerenciamento de Oficina

Este projeto define o esquema conceitual de um sistema para gerenciar o controle de ordens de serviço em uma oficina mecânica. O objetivo é possibilitar o acompanhamento de clientes, veículos, mecânicos, serviços e peças, bem como a execução e controle de cada ordem de serviço (OS).

## Descrição do Contexto

O sistema de gerenciamento de ordens de serviço permite:
1. Cadastrar clientes e seus veículos.
2. Designar veículos a equipes de mecânicos, que realizam a análise e execução de serviços.
3. Gerar ordens de serviço que detalham os serviços e peças necessárias para cada veículo.
4. Calcular o valor total da ordem de serviço com base nos serviços e peças utilizados.

## Entidades Principais

- **Cliente**: Armazena as informações de cada cliente.
- **Veículo**: Registra os veículos dos clientes e os associa a eles.
- **Mecânico** e **Equipe**: Gerenciam as equipes e seus respectivos mecânicos.
- **Ordem_Serviço (OS)**: Representa o documento que detalha os serviços e peças para cada atendimento.
- **Serviço** e **Peça**: Referenciam a tabela de serviços e peças com seus valores.

## Estrutura do Projeto

O projeto está estruturado com entidades e relacionamentos de forma a permitir o controle efetivo do fluxo de trabalho na oficina. Ele também inclui tabelas de relacionamento para permitir operações N:N, como a associação de mecânicos a equipes e de serviços e peças a ordens de serviço.

## Nota

Caso o sistema evolua, podem ser adicionadas funcionalidades para controle de inventário de peças, gestão de disponibilidade de mecânicos e histórico detalhado de manutenção de cada veículo.
