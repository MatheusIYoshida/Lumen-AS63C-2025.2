# 1. Requisitos Funcionais

<p align="justify">A <i>Tabela 1</i> a seguir contém os Requisitos Funcionais (RF) elicitados utizando a técnica de Brainstorm.</p>

| ID   |                                      Requisito                                      | Prioridade | Requisitos Relacionados |
| :--: | :----------------------------------------------------------------------------------: | :--------: | :---------------------: |
| RF01 | O usuário deve poder cadastrar-se (registro) no aplicativo.                         |    Alta    | RF02, RF18              |
| RF02 | O usuário deve poder logar/logout com credenciais próprias.                         |    Alta    | RF01, RF18              |
| RF03 | O usuário deve poder criar uma nova tarefa com título, descrição e data/hora.        |    Alta    | RF05, RF06, RF07        |
| RF04 | O usuário deve poder editar os campos de uma tarefa existente.                      |    Média   | RF03, RF05              |
| RF05 | O usuário deve poder atribuir prioridade à tarefa (ex: Baixa, Média, Alta).         |    Alta    | RF03, RF11              |
| RF06 | O usuário deve poder classificar a tarefa por tipo/categoria (Trabalho, Casa, Estudo, Saúde, Outros). |    Média   | RF03, RF12              |
| RF07 | O usuário deve poder definir data de vencimento e horário de conclusão esperado.    |    Alta    | RF03, RF13              |
| RF08 | O usuário deve poder marcar uma tarefa como resolvida/concluída.                    |    Alta    | RF03, RF09              |
| RF09 | O usuário deve poder visualizar histórico de tarefas concluídas (com data).         |    Média   | RF08, RF20              |
| RF10 | O usuário deve poder excluir uma tarefa permanentemente.                            |    Média   | RF03                    |
| RF11 | O usuário deve poder filtrar/consultar tarefas por prioridade, tipo, data, status (concluída/pendente) e intervalo de datas. |    Alta    | RF03, RF05, RF06        |
| RF12 | O usuário deve poder pesquisar tarefas por texto (título/descrição).                |    Média   | RF11                    |
| RF13 | O usuário deve poder configurar tarefas recorrentes: diária, semanal e mensal (com regras de repetição). |    Alta    | RF03, RF14              |
| RF14 | O sistema deve criar automaticamente instâncias futuras de tarefas recorrentes e permitir edição de ocorrência individual ou série. |    Alta    | RF13, RF08              |
| RF15 | O usuário deve poder visualizar suas tarefas em uma visualização de calendário (mês/semana/dia). |    Alta    | RF03, RF13              |
| RF16 | O usuário deve receber lembretes/alertas por push/notification (ou e-mail) antes do vencimento da tarefa. |    Alta    | RF03, RF07              |
| RF17 | O usuário deve poder adiar/snooze um lembrete ou reagendar uma tarefa rapidamente.  |    Média   | RF16, RF04              |
| RF20 | O usuário deve poder anexar arquivos/imagens a uma tarefa.                          |    Baixa   | RF03, RF09              |
| RF22 | O usuário deve poder compartilhar uma tarefa ou lista com outros usuários (colaboração). |    Média   | RF01, RF02, RF18        |
| RF23 | O sistema deve permitir configurar exceções para recorrências (p.ex.: pular data, alterar uma ocorrência específica). |    Média   | RF13, RF14              |
| RF24 | O usuário deve poder visualizar indicadores simples (ex.: tarefas concluídas no período, próximas tarefas). |    Baixa   | RF09, RF15              |
| RF25 | O aplicativo deve enviar notificações de sincronização/erro ao usuário quando ocorrerem conflitos de dados. |    Baixa   | RF18              |
| RF26 | O usuário deve poder ordenar a lista de tarefas por data, prioridade, ou ordem manual arrastando e soltando. |    Média   | RF05, RF11              |



<div style="text-align: center">
<p>Tabela 1: Requisitos Funcionais</p>
</div>

# 2. Referências


<a href="../README.md">VOLTAR INÍCIO</a>
