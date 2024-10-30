# Documento de Requisitos do Task Manager

Esta documentação tem como objetivo detalhar os requisitos para o desenvolvimento de um Sistema de Gerenciamento de Tarefas (SGT). O sistema será uma aplicação web desenvolvida com ASP.NET MVC, que visa facilitar o gerenciamento de tarefas por meio de uma interface intuitiva, oferecendo funcionalidades para criação, edição, visualização e exclusão de tarefas. Este projeto faz parte de um treinamento, e contempla três módulos já abordados: 
  1 - Introdução ao ASP.NET MVC.
  2 - Roteamento no ASP.NET MVC.
  3 - HTML Helpers no ASP.NET MVC.

## Objetivo

O objetivo principal do SGT é disponibilizar uma interface simples e eficiente para a administração de tarefas, possibilitando que usuários realizem operações como criação, edição, visualização e exclusão de tarefas.

## Descrição:

O SGT deve ser desenvolvido com o padrão de arquitetura ASP.NET MVC. Ele permitirá aos usuários adicionar, editar, visualizar e remover tarefas, com foco na aplicação prática dos conceitos vistos nos módulos do curso.

## Requisitos do Projeto:
- Listar Tarefas: Exiba uma lista de tarefas com título, descrição e status de conclusão.
- Criar Nova Tarefa: Permita ao usuário adicionar novas tarefas com título, descrição e status (concluída ou não).
- Editar Tarefa: Implementar uma funcionalidade para editar uma tarefa existente.
- Excluir Tarefa: Adicionar uma opção de deletar uma tarefa após confirmação.
- Visualizar Detalhes: Permitir a visualização dos detalhes de uma tarefa específica.
  
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
   
- **Tarefas**:
    - Página principal para manipulação de tarefas, incluindo a listagem e as opções de criação, edição e exclusão de tarefas.
   
## Observação

Solicitamos que façam o uso do Node JS em uma versão 18 ou superior


## O que será avaliado? 

No geral, tudo será avaliado. Porém nosso foco é descobrir como você aplica os conceitos da programação nos seus projetos, como você soluciona problemas e como irá gerar valor ao produto desenvolvido.

- Estrutura do Código: Organização e clareza do código.
- Cumprimento de Requisitos: Atendimento aos requisitos especificados.
- Lógica de Programação: Soluções implementadas e sua eficiência.
- Metodologia Aplicada: Abordagem para resolver problemas e entregar valor.
- Criatividade: Criatividade na solução dos requisitos propostos.

## Entrega

Faça o projeto calmamente e organizadamente! Focando sempre no seu aprendizado, lembrem-se, estamos aqui para aprender. 

- **OBS**: Faça commits claros e descritivos, estaremos atentos a cada detalhe do seu desenvolvimento.

## Checklist 📝

Abaixo estão as implementações que terão de ser feitas no seu projeto. Quanto mais itens você entregar, melhor será sua avaliação. Utilize este checklist como um guia e faça os itens que conseguir.

Os itens estão separados por níveis, e o nível 1 é o mínimo que esperamos que vocês entreguem. Considerem diferenciais para este primeiro projeto itens do nível 2 em diante.


---

**Legenda:**

- B -> Backend
- F -> Frontend

---

### Nível 1

|     | Descrição                  | Local |
| --- | -------------------------- | ----- |
| [ ] | Listar projetos            |  F B  |
| [ ] | Cadastrar um projeto       |  F B  |
| [ ] | Editar um projeto          |  F B  |
| [ ] | Remover um projeto         |  F B  |
| [ ] | Listar usuários em projetos             |  F B  |
| [ ] | Cadastrar usuários em projetos       |  F B  |
| [ ] | Remover usuários em projetos         |  F B  |
| [ ] | Tipagem de dados           |  F B  |
| [ ] | Registro de usuários no sistema     |  F B  |
| [ ] | Autenticação via login         |  F B  |
| [ ] | Validações de campos     |  F B  |


### Nível 2

|     | Descrição	                                            | Local |
| --- | ------------------------------------------------      | ----- |
| [ ] |	Tratamento de exceções / Retornos erros concisos	    |  F B  |
| [ ] | Mensagens de sucesso e/ou erros	                      |  F   |
| [ ] | Impedir remoção de projetos não concluídos            |   B   |
| [ ] | Paginação na listagem de projetos	                    |  F B  |
| [ ] | Paginação na listagem de usuários	                    |  F B  |
| [ ] | Confirmação para exclusão de itens	                  |  F   |


### Nível 3

|     | Descrição                              | Local |
| --- | -------------------------------------- | ----- |
| [ ] | Testes de integração                   |    B  |
| [ ] | Organização e estrutura de pastas      |  F B  |
| [ ] | Clean Code                             |  F B  |

### Nível 4

|     | Descrição                                                               | Local |
| --- | ----------------------------------------------------------------------- | ----- |
| [ ] | Disponibilização do backend via Containers                              |    B  |
| [ ] | Disponibilização do frontend via Containers                             |  F    |
| [ ] | Disponibilização dos containers (backend + frontend)                    |  F B  |



