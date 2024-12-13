# To-Do Task Manager

## Descrição
O **To-Do Task Manager** é um aplicativo para controle de tarefas. Ele possibilita que os usuários criem, organizem, atualizem e vejam tarefas de maneira eficiente, com recursos como visualização em Kanban e apoio a projetos.

---
## Funcionalidades Principais

### Relacionamento Pai/Filho entre Tarefas
- Criar hierarquias de tarefas, permitindo que uma tarefa tenha subtarefas.  
- Subtarefas também podem ter suas próprias subtarefas, formando uma hierarquia ilimitada.

### Movimentação de Tarefas no Kanban
- Permitir arrastar e soltar tarefas entre as raias para atualizar seu status.

### Visualização Kanban com Raias Customizáveis
- Visualizar tarefas em um quadro Kanban com raias iniciais: **Backlog**, **In Progress** e **Done**.  
- Personalizar o Kanban, possibilitando:  
  - Adicionar novas raias.  
  - Renomear raias existentes.  
  - Excluir raias (exceto as obrigatórias).

### Reorganização de Tarefas
- Reorganizar tarefas, alterando sua ordem e prioridades.

### Organização em Projetos
- Organizar tarefas dentro de projetos, cada projeto contendo suas próprias tarefas e subtarefas.
---

## Requisitos Não Funcionais
- **Performance**: Operações rápidas e eficientes, mesmo com muitos dados.
- **Responsividade**: Compatível com dispositivos móveis e desktops.
- **Escalabilidade**: Preparado para múltiplos usuários simultaneamente.
- **Manutenibilidade**: Código limpo e bem documentado.

---
## User Stories

1. **Criar Hierarquia de Tarefas**  
   - **Eu como** usuário  
   - **Quero** criar subtarefas relacionadas a uma tarefa principal  
   - **Para que** eu consiga organizar atividades complexas em partes menores.

2. **Mover Tarefas no Kanban**  
   - **Eu como** usuário  
   - **Quero** arrastar e soltar tarefas entre as raias do Kanban  
   - **Para que** eu possa atualizar o status de cada tarefa rapidamente.

3. **Personalizar Raias do Kanban**  
   - **Eu como** usuário  
   - **Quero** adicionar, renomear e excluir raias no Kanban (exceto as obrigatórias)  
   - **Para que** eu possa adaptar o quadro às minhas necessidades específicas.

4. **Reorganizar Tarefas**  
   - **Eu como** usuário  
   - **Quero** alterar a ordem das tarefas em uma raia  
   - **Para que** eu possa priorizar atividades importantes.

5. **Organizar Tarefas por Projetos**  
   - **Eu como** usuário  
   - **Quero** criar projetos e associar tarefas a eles  
   - **Para que** eu consiga organizar tarefas relacionadas a diferentes contextos ou objetivos.
---

## Stack Tecnológica

- **Frontend**:  
  - **HTML5**: Estruturação do layout.  
  - **CSS3**: Estilização do sistema, utilizando técnicas como Flexbox ou Grid para organizar os elementos.  
  - **JavaScript**: Implementação da lógica para criação, gerenciamento e movimentação de tarefas.

- **Armazenamento**:  
  - **LocalStorage**: Para salvar as tarefas diretamente no navegador, garantindo persistência local.



   
