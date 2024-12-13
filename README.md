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

1. **Performance**:  
   - O sistema deve ser capaz de gerenciar múltiplas tarefas, incluindo subtarefas e hierarquias complexas, sem comprometer o desempenho.

2. **Usabilidade**:  
   - A interface deve ser intuitiva, permitindo a movimentação de tarefas no Kanban por meio de drag-and-drop.  
   - As opções de personalização (criação e edição de raias) devem ser acessíveis e fáceis de usar.

3. **Escalabilidade**:  
   - O sistema deve suportar a criação de múltiplos projetos, cada um contendo suas próprias tarefas e subtarefas.

4. **Portabilidade**:  
   - O sistema deve ser responsivo, funcionando bem em dispositivos móveis, tablets e desktops.

5. **Persistência de Dados**:  
   - Todas as tarefas, subtarefas, raias e projetos personalizados devem ser armazenados no **LocalStorage**, garantindo que as informações sejam mantidas mesmo após a página ser recarregada.

6. **Manutenibilidade**:  
   - O código deve ser modular e bem documentado, facilitando futuras melhorias ou correções.

7. **Feedback ao Usuário**:  
   - O sistema deve fornecer notificações visuais claras (como cores ou animações) para confirmar ações como movimentação, criação ou exclusão de tarefas.

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



   
