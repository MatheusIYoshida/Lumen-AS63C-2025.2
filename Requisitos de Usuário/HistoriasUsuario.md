# 1. História de Usuário

A Tabela a seguir contém as Histórias de Usuário elicitadas. 

<table>
    <thead>
        <tr style="background-color: purple; color: white">
            <th style="border-style:solid;border-width:1px;text-align:center">ID</th>
            <th style="border-style:solid;border-width:1px;text-align:center">História de Usuário</th>
            <th style="border-style:solid;border-width:1px;text-align:center">Critérios de Aceitação</th>
            <th style="border-style:solid;border-width:1px;text-align:center">Prioridade</th>
            <th style="border-style:solid;border-width:1px;text-align:center">RF/RNF Relacionado</th>
            <th style="border-style:solid;border-width:1px;text-align:center">Story Points</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US01</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como novo usuário, quero poder me cadastrar no aplicativo para criar e gerenciar minhas tarefas.</td>
            <td style="border-style:solid;border-width:1px;vertical-align:top">
                <ol>
                    <li>O cadastro deve exigir e-mail, senha e nome do usuário.</li>
                    <li>Deve exibir mensagem de sucesso ou erro.</li>
                    <li>Os dados devem ser validados (e-mail único e senha forte).</li>
                </ol>
            </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF01</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">5</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US02</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário registrado, quero fazer login e logout com minhas credenciais para acessar minhas tarefas com segurança.</td>
            <td style="border-style:solid;border-width:1px;vertical-align:top">
                <ol>
                    <li>O login deve validar e-mail e senha.</li>
                    <li>Permitir logout a qualquer momento.</li>
                    <li>Mostrar mensagem de erro em caso de credenciais inválidas.</li>
                </ol>
            </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF02</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">5</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US03</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário, quero criar novas tarefas com título, descrição e data/hora para organizar minhas atividades.</td>
            <td style="border-style:solid;border-width:1px;vertical-align:top">
                <ol>
                    <li>Permitir inserir título, descrição e data/hora obrigatórios.</li>
                    <li>Exibir confirmação após salvar a tarefa.</li>
                </ol>
            </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF03</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">8</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US04</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário, quero editar ou excluir tarefas existentes para manter minha lista sempre atualizada.</td>
            <td style="border-style:solid;border-width:1px;vertical-align:top">
                <ol>
                    <li>Permitir alterar título, descrição, data/hora, prioridade e categoria.</li>
                    <li>Confirmação antes da exclusão definitiva.</li>
                </ol>
            </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Média</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF04, RF10</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">8</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US05</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário, quero atribuir prioridade e categoria às tarefas para organizar melhor minhas atividades.</td>
            <td style="border-style:solid;border-width:1px;vertical-align:top">
                <ol>
                    <li>Permitir selecionar prioridade (Baixa, Média, Alta).</li>
                    <li>Permitir escolher categoria (Trabalho, Casa, Estudo, Saúde, Outros).</li>
                    <li>As opções devem ser editáveis posteriormente.</li>
                </ol>
            </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF05, RF06</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">5</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US06</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário, quero receber lembretes antes do vencimento de cada tarefa para não perder prazos.</td>
            <td style="border-style:solid;border-width:1px;vertical-align:top">
                <ol>
                    <li>Enviar notificação push ou e-mail antes da data de vencimento.</li>
                    <li>Permitir definir tempo de antecedência do alerta.</li>
                </ol>
            </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF16</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">8</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US07</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário, quero visualizar minhas tarefas em formato de calendário para ter uma visão geral do mês ou semana.</td>
            <td style="border-style:solid;border-width:1px;vertical-align:top">
                <ol>
                    <li>Disponibilizar visualização por mês, semana e dia.</li>
                    <li>Permitir navegação entre períodos.</li>
                </ol>
            </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF15</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">8</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US08</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário, quero compartilhar tarefas com outros usuários para colaboração em equipe.</td>
            <td style="border-style:solid;border-width:1px;vertical-align:top">
                <ol>
                    <li>Permitir convite por e-mail ou link.</li>
                    <li>Definir permissões de edição ou visualização.</li>
                </ol>
            </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Média</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF19</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">13</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US09</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Como usuário comum, eu quero criar tarefas com título, descrição, data e prioridade, para organizar melhor minhas atividades pessoais e profissionais.</td>
            <td style="border-style:solid;border-width:1px;vertical-align:top">
                <ol>
                    <li>Deve ser possível adicionar uma nova tarefa com título obrigatório.</li>
                    <li>O usuário pode incluir descrição, data de vencimento e prioridade (baixa, média, alta).</li>
                    <li>O sistema deve salvar e exibir a tarefa imediatamente após a criação.</li>
                </ol>
            </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF03, RF05, RF07</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">8</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US10</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Como usuário comum, eu quero adicionar categorias e etiquetas às minhas tarefas, para organizar e localizar atividades de forma mais rápida.</td>
            <td style="border-style:solid;border-width:1px;vertical-align:top">
                <ol>
                    <li>Deve ser possível criar e editar categorias personalizadas.</li>
                    <li>O usuário pode atribuir uma ou mais etiquetas a cada tarefa.</li>
                    <li>O sistema deve permitir filtrar tarefas por categoria e etiquetas.</li>
                </ol>
            </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Média</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF06, RF11</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">5</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US11</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Como usuário comum, eu quero receber notificações sobre o vencimento das minhas tarefas, para não esquecer prazos importantes.</td>
            <td style="border-style:solid;border-width:1px;vertical-align:top">
                <ol>
                    <li>O usuário deve poder configurar lembretes (ex.: 1 hora antes, 1 dia antes).</li>
                    <li>O sistema deve enviar notificações push no celular e alertas no desktop.</li>
                    <li>Notificações só devem ser disparadas para tarefas com data de vencimento configurada.</li>
                </ol>
            </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF16</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">8</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US12</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Como usuário comum, eu quero compartilhar listas de tarefas com outras pessoas, para colaborar em projetos em grupo.</td>
            <td style="border-style:solid;border-width:1px;vertical-align:top">
                <ol>
                    <li>O usuário deve poder convidar outros usuários para uma lista específica via e-mail ou link.</li>
                    <li>Usuários convidados podem visualizar, adicionar e editar tarefas (dependendo da permissão concedida).</li>
                    <li>Alterações devem ser refletidas em tempo real para todos os membros da lista.</li>
                </ol>
            </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Média</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF19</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">13</td>
        </tr>
    </tbody>
</table>

<div style="text-align: center">
<p>Tabela: Histórias de Usuário</p>
</div>

## 5. Referências Bibliográficas
