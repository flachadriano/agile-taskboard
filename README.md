# Agile Taskboard

## Escopo do projeto

Versão 1

Qualquer usuário pode cadastrar projeto
Qualquer usuário pode realizar alterações nos cadastros

Projeto
- Qualquer usuário pode adicionar Colaboradores
- Qualquer usuário pode adicionar Histórias

Task
- Na linha To Do, qualquer usuário pode alterar para Iniciar Tarefa
- Na linha In Progresso, qualquer usuário que ainda não tenha iniciado essa tarefa pode Iniciar Tarefa e alguém que já a tenha iniciado pode Finalizar Tarefa ou Parar Tarefa
- Na linha Done, o usuário pode alterar o status para Revisar Tarefa
- Atividades que já tiveram algum tempo de desenvolvimento não podem ser deletadas, é solicitado se deseja cancelá-la, manda para a área de canceladas

Versão 2

Somente o usuário Master pode adicionar Colaboradores ao projeto, ou usuário autorizados
Somente usuário Master pode fazer alterações em cadastros

## Etapas de desenvolvimento

Etapa 1

- Criar projeto, informando somente
- Criar sprint
- Adicionar história no Sprint
- Adicionar tarefa no Sprint
- Trilhas TO DO, Doing, Done
- Quando alterar tarefa para Doing, iniciar histórico de atividade
- Quando remover tarefa para Doing, finalizar histórico de atividade
- Finalizar/iniciar Sprint. voltar tarefas para novo Sprint

Etapa 2

- Criar pilha de tarefas futuras
- Adicionar histórico, quando muda de sprint
- Adicionar comentários
- Compartilhamento de projetos
- Adicionar prioridade na tarefa

## Class Diagram

![Screenshot](https://raw.githubusercontent.com/flachadriano/agile-taskboard/master/documentation/class.png)

## Views (Prototype)

developed with http://lumzy.com/app/

![Screenshot](https://raw.githubusercontent.com/flachadriano/agile-taskboard/master/views/sign-up.jpg)
![Screenshot](https://raw.githubusercontent.com/flachadriano/agile-taskboard/master/views/sign-in.jpg)
-----------------------------------------------------------------------------------------------------------------
![Screenshot](https://raw.githubusercontent.com/flachadriano/agile-taskboard/master/views/projects.jpg)
![Screenshot](https://raw.githubusercontent.com/flachadriano/agile-taskboard/master/views/project-new.jpg)
-----------------------------------------------------------------------------------------------------------------
![Screenshot](https://raw.githubusercontent.com/flachadriano/agile-taskboard/master/views/collaborators.jpg)
-----------------------------------------------------------------------------------------------------------------
![Screenshot](https://raw.githubusercontent.com/flachadriano/agile-taskboard/master/views/groups.jpg)
![Screenshot](https://raw.githubusercontent.com/flachadriano/agile-taskboard/master/views/group-new.jpg)
![Screenshot](https://raw.githubusercontent.com/flachadriano/agile-taskboard/master/views/group.jpg)
![Screenshot](https://raw.githubusercontent.com/flachadriano/agile-taskboard/master/views/group-history-new.jpg)
-----------------------------------------------------------------------------------------------------------------
![Screenshot](https://raw.githubusercontent.com/flachadriano/agile-taskboard/master/views/taskboard.jpg)
![Screenshot](https://raw.githubusercontent.com/flachadriano/agile-taskboard/master/views/taskboard-history.jpg)
![Screenshot](https://raw.githubusercontent.com/flachadriano/agile-taskboard/master/views/taskboard-task.jpg)