# To-Do Task Manager

## Descrição
O **To-Do Task Manager** é uma aplicação para gerenciamento de tarefas. Ele permite aos usuários criar, organizar, atualizar e visualizar tarefas de forma eficiente, com funcionalidades como visualização em Kanban e suporte a projetos.

---

## Funcionalidades Principais
- **Adicionar Tarefa**: Criação de tarefas com título, descrição e prazo opcional.
- **Gerenciar Status**: Alteração do status das tarefas (*Pendente*, *Em Progresso*, *Concluído*).
- **Kanban com Raias Customizáveis**: Organização visual por categorias ou projetos.
- **Relacionamento Pai/Filho**: Criação de subtarefas relacionadas a uma tarefa principal.
- **Gerenciamento de Projetos**: Agrupamento de tarefas em projetos específicos.

---

## Requisitos Não Funcionais
- **Performance**: Operações rápidas e eficientes, mesmo com muitos dados.
- **Responsividade**: Compatível com dispositivos móveis e desktops.
- **Escalabilidade**: Preparado para múltiplos usuários simultaneamente.
- **Manutenibilidade**: Código limpo e bem documentado.

---

## User Stories
1. **Adicionar Tarefa**
   - **Eu como** usuário
   - **Quero** adicionar uma nova tarefa
   - **Para que** eu possa planejar minhas atividades.

2. **Atualizar Status**
   - **Eu como** usuário
   - **Quero** mudar o status de uma tarefa para "Concluído"
   - **Para que** eu possa acompanhar meu progresso.

3. **Criar Subtarefas**
   - **Eu como** usuário
   - **Quero** adicionar subtarefas relacionadas a uma tarefa maior
   - **Para que** eu consiga detalhar atividades complexas.

---

## Stack Tecnológica
- **Frontend**: React.js com Tailwind CSS (se aplicável).
- **Backend**: Node.js com Express.js.
- **Banco de Dados**: MongoDB ou PostgreSQL.
- **Testes**: Jest para backend, Cypress para frontend.
- **Deploy**: Vercel (frontend) e Heroku (backend).
- **Gerenciamento**: Jira ou Trello para controle de tarefas.

---

## Como Rodar o Projeto
1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/to-do-task-manager.git
   cd to-do-task-manager
   
