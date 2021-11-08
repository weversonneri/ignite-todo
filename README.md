# Desafio 01 Ignite ReactJS

<p align="center">
  <img 
    src="https://user-images.githubusercontent.com/53442803/140808397-c2be83f5-aba8-4408-9529-ea1b9aff7455.gif"
    width="70%"
  />
</p>

Desafio proposto para praticar os topicos abordados no Ignite Chapter I da trilha de ReactJS.

Essa será uma aplicação onde o seu principal objetivo é uma pequena aplicação de atividades a fazer, para treinar um pouco mais sobre manipulação do estado no React.

- Adicionar uma nova tarefa
- Remover uma tarefa
- Marcar e desmarcar uma tarefa como concluída

## Objetivo
Clonar o template disponibilizado e completar as seguintes funcionalidades da aplicação: 
- [x] **handleCreateNewTask**: Deve ser possível adicionar uma nova task no estado de `tasks`, com os campos `id` que deve ser gerado de forma aleatória, `title` que deve ser um texto e `isComplete` que deve iniciar como false.
- [x] **handleToggleTaskCompletion:** Deve alterar o status de `isComplete` para uma task com um ID específico que é recebido por parâmetro.
- [x] **handleRemoveTask:** Deve receber um ID por parâmetro e remover a task que contém esse ID do estado.