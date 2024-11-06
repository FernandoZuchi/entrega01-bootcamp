# Documento de Requisitos do Task Manager

Esta documentação tem como objetivo detalhar os requisitos para o desenvolvimento de um Sistema de Gerenciamento de Solicitações de Suporte e Problemas Técnicos (SGSSPT). O sistema será uma aplicação web desenvolvida com ASP.NET MVC, que visa facilitar o gerenciamento de chamados por meio de uma interface intuitiva, oferecendo funcionalidades para criação, edição, visualização e exclusão de chamados de suporte. Este projeto faz parte de um treinamento, e contempla três módulos já abordados: 
- 1: Introdução ao ASP.NET MVC.
- 2: Roteamento no ASP.NET MVC.
- 3: HTML Helpers no ASP.NET MVC.

## Objetivo

O objetivo do Sistema de Helpdesk é fornecer uma plataforma intuitiva e eficiente para gerenciar solicitações de suporte e problemas técnicos, permitindo que as equipes de TI e suporte respondam prontamente às solicitações dos usuários. A aplicação será desenvolvida em ASP.NET MVC e será utilizada para treinamento, abordando os fundamentos do framework.

## Descrição:

O Sistema de Helpdesk será uma aplicação web, estruturada em ASP.NET MVC, permitindo aos usuários criar, visualizar, atualizar e excluir tickets de suporte. O sistema tem como meta aplicar os conceitos fundamentais do framework e servir como base para aprimoramentos futuros, com escalabilidade em mente.

## Requisitos do Projeto:
- Listagem de Tickets (Chamados): Permitir que os usuários visualizem uma lista de todos os tickets, exibindo informações como título, descrição, status, prioridade e data de abertura.
- Criação de Novo Ticket (Chamados): Fornecer uma interface para criação de tickets, com campos para título, descrição, prioridade, data de abertura e status (aberto, em andamento, fechado).
- Edição de Ticket (Chamados): Possibilitar a atualização de informações de um ticket existente, como descrição, prioridade e status.
- Exclusão de Ticket (Chamados): Permitir a remoção de tickets com uma confirmação para evitar exclusões acidentais.
- Visualização Detalhada: Fornecer uma página de detalhes onde o usuário possa ver informações completas de um ticket específico.
  
## Dicas:
- Utilizem os padrões do ASP.NET MVC para cumprir os requisitos
- A lista de tarefas pode ser armazenada em uma lista estática para esta versão inicial, sem necessidade de banco de dados.
- Procurem adaptar o desenvolvimento de vocês utilizando o máximo de conceitos aprendidos no nosso treinamento até aqui.
- Procurem não implementar muitas coisas além do que está sendo pedido nessa primeira entrega, para próximas entregas, talvez serão solicitadas implementações novas neste mesmo projeto, logo, faça seu código pensando na escalabilidade.


## Tecnologias/tópicos obrigatórios
- **ASP.NET MVC 5**
- **.NET Framework 4.8**
- **Roteamento do ASP.NET MVC 5**
- **HTML Helpers nas Views, com sintaxe Razor**


## **Páginas:**
   
- **Listagem de Tickets**:
    - Interface principal com a lista de tickets e opções para adicionar, editar e excluir.
 
- **Página de Criação/Edição de Tickets**:
    - Formulário para criação de um novo ticket ou edição de um ticket existente.

- **Página de Vizualização Detalhada**:
    - Mostra detalhes completos de um ticket específico.

## O que será avaliado? 

- Estrutura do Código: Organização e clareza do código.
- Cumprimento de Requisitos: Atendimento aos requisitos especificados.
- Lógica de Programação: Soluções implementadas e sua eficiência.
- Metodologia Aplicada: Abordagem para resolver problemas e entregar valor.
- Criatividade: Criatividade na solução dos requisitos propostos.

## Entrega

Faça o projeto calmamente e organizadamente! Focando sempre no seu aprendizado, lembrem-se, estamos aqui para aprender. 

- **OBS**: Faça commits claros e descritivos, estaremos atentos a cada detalhe do seu desenvolvimento.

## Checklist 📝

Abaixo temos um checklist para te ajudar no cumprimento de requisitos do projeto:


|     | Descrição                  |
| --- | -------------------------- |
| [ ] | Listar tickets(chamados)          |  
| [ ] | Criar novo ticket       |
| [ ] | Editar ticket    |    
| [ ] | Remover ticket       | 
| [ ] | Visualizar detalhes do ticket    |        



