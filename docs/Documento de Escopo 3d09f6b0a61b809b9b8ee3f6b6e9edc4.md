# Documento de Escopo

Projeto  ToDoList

Objetivo do projeto: O objetivo do projeto **EsToDoList do Estudante** é criar uma lista de tarefas simples, prática e fácil de usar, que ajude os estudantes a organizar melhor suas atividades e compromissos.

### Requisitos Funcionais

**RF01 - Cadastrar Tarefa:** O usuário poderá adicionar uma nova tarefa colocando o nome da atividade, a data de entrega e, se quiser, uma descrição ou horário. Depois de preencher os dados, basta clicar em salvar para a tarefa aparecer na lista.

**RF02 - Editar Tarefa:** Se o usuário colocar alguma informação errada ou quiser mudar a tarefa, ele poderá clicar em editar. Assim, poderá alterar o nome, a data ou outras informações e salvar novamente.

**RF03 - Excluir Tarefa:** Quando o usuário não precisar mais de uma tarefa, poderá excluí-la clicando no botão de excluir. 

**RF04 - Marcar Tarefa como Concluída:** Quando terminar uma tarefa, o usuário poderá marcá-la como concluída. Ela ficará diferente das tarefas que ainda estão pendentes.

**RF05 - Pesquisar/Filtrar Tarefas:** Para encontrar uma tarefa mais rapidamente, o usuário poderá usar uma barra de pesquisa. Também poderá filtrar a lista para ver apenas tarefas pendentes ou concluídas, facilitando a organização.

### Requisitos Não Funcionais

**RNF01 - Responsividade:** O sistema deve funcionar bem em computadores, tablets e celulares. **Isso é importante porque** os alunos podem acessar suas tarefas em diferentes dispositivos durante o dia.

**RNF02 - Facilidade de Uso:** O sistema deve ter uma interface simples e fácil de entender. **Isso é importante porque** o aluno precisa conseguir cadastrar e organizar suas tarefas sem perder muito tempo aprendendo a usar o sistema.

**RNF03 - Desempenho:** O sistema deve carregar rapidamente e responder aos comandos do usuário em pouco tempo. **Isso é importante porque** ninguém quer ficar esperando para adicionar, editar ou concluir uma tarefa.

### Fora de Escopo

**1. Notificações e lembretes:** O sistema poderia enviar notificações para avisar sobre tarefas próximas do prazo, mas essa função ficará de fora da primeira versão **porque queremos focar primeiro nas funções básicas e manter o projeto mais simples**.

**2. Login e conta de usuário:** Seria interessante permitir que cada aluno tivesse uma conta para acessar suas tarefas em diferentes dispositivos, mas essa função não fará parte da primeira versão **porque exigiria um sistema de cadastro e banco de dados.**

Cascata

| REQUISITOS | ANÁLISE E PROJETO | DESENVOLVIMENTO | TESTES | IMPLANTAÇÃO E MANUTENÇÃO |
| --- | --- | --- | --- | --- |
| Entrevistar alunos
para entender como
eles organizam suas
tarefas hoje. | Definir a paleta de
cores e a fonte que
serão usadas no site. | Programar a função
em JavaScript que
salva uma nova t    arefa
no navegador. | Tentar "quebrar" o
campo de data,
inserindo um texto em
vez de um número. | Corrigir um bug
reportado por um
usuário uma semana
após o lançamento. |
| Escrever o
Documento de Escopo
com todas as
funcionalidades. | Desenhar as telas
do aplicativo no | Escrever o código
HTML da página
principal. | Verificar se o
aplicativo funciona
corretamente nos
navegadores Chrome | Publicar a versão
final do site em um
servidor online para
que todos possam

usar. |
| Mapear e detalhar os Requisitos Não Funcionais (Responsividade, Facilidade de Uso e Desempenho). | Criar o *wireframe* (esboço visual) das telas de cadastro, edição e listagem de tarefas para celulares e computadores. | Criar os estilos CSS para destacar as tarefas marcadas como concluídas das pendentes. | Testar a interface em telas de diferentes tamanhos (celular, tablet e computador) para validar a responsividade. | Monitorar o tempo de carregamento e o desempenho geral da aplicação no servidor online. |
| Definir as regras das funcionalidades que ficaram fora do escopo (notificações e sistema de login) para versões futuras. | Elaborar o fluxo de navegação do usuário ao cadastrar, editar, filtrar e excluir uma tarefa. | Implementar a barra de pesquisa e os filtros de tarefas pendentes/concluídas em JavaScript. | Realizar testes de usabilidade com 3 estudantes para verificar se a interface é simples e intuitiva. | Atualizar a documentação do projeto com instruções de uso e guia para futuras melhorias. |

A Matriz de Risco

| Probabiidade | ALTA | MÉDIA | ALTA | ALTA |  |
| --- | --- | --- | --- | --- | --- |
|  | MÉDIA | BAIXA | MÉDIA | ALTA |  |
|  | BAIXA | BAIXA | BAIXA | MÉDIA |  |
|  |  | BAIXO | MÉDIO | ALTO |  |
|  |  | IMPACTO |  |  |  |

| Risco ( Descrição)  | Probabilidade
(Baixa/Alta) | Impacto
(Baixo/Alto) | Plano de ação ( O que faremos para prevenir ou remediar?) |
| --- | --- | --- | --- |
| Ex: O unico programador do projeto dfica doente e se ausenta por uma semana. Risco de recursos | Baixa | Alto | Plano de ação: Manter toda a documentação do projeto atualizada e salva em um local compartilhado   (como o notion) para que outra pessoa possa entender o andamento. |
| Risco 1:  e se todo o código desenvolvido em uma aula fosse perdido porque ninguém fez commit ou enviou o projeto para o GitHub? | Baixa | Alto | Crie o repositório git nos primeiros minutos de aula e adote pausas periódicas para salvar o progresso na nuvem. |
| Risco 2: Internet Indisponivel no momento da entrega/apresentação | Alta | Alto | Baixar os conteúdos em um pendrive, ou entregar as atividades antes do prazo. |
| RIsco 3: Durante o desenvolvimento do EsToDoList, os alunos que testaram o sistema gostaram da ideia e começaram a pedir um chat para conversar sobre as tarefas? | Alta | Altox’11x’ | Eu falaria não e manteria o sistema simples e focado no objetivo principal evitando essa complexidade técnica no meio do projeto. |