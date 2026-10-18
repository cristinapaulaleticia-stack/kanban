# Biblioteca Escolar — Projeto com Kanban

## Objetivo
Planejar e demonstrar um sistema simples para gerenciamento de uma biblioteca escolar usando a metodologia Kanban.

## Funcionalidades
- Cadastro de livros e quantidades.
- Cadastro de alunos e turmas.
- Registro de empréstimos.
- Registro de devoluções.
- Consulta de livros disponíveis.
- Relatório simples com empréstimos em aberto e devolvidos.

## Como executar
1. Baixe ou clone este repositório.
2. Abra o arquivo `index.html` em um navegador (Chrome, Edge ou Firefox).
3. Cadastre alguns livros e alunos para demonstrar o funcionamento.
4. Registre um empréstimo, depois registre a devolução e consulte o relatório.

Os dados desta demonstração ficam no armazenamento local do navegador (`localStorage`). É um protótipo escolar: não possui login, servidor ou banco de dados compartilhado.

## Planejamento usando Kanban

O quadro utiliza as colunas **A Fazer**, **Em andamento**, **Em teste** e **Concluído**. As tarefas devem ser movidas conforme o trabalho avança. A equipe pode usar o GitHub Projects para criar esse quadro e registrar os responsáveis.

### Backlog inicial (A Fazer)
- [ ] Definir os requisitos da biblioteca.
- [ ] Criar a estrutura visual da página.
- [ ] Implementar cadastro de livros.
- [ ] Implementar cadastro de alunos.
- [ ] Implementar empréstimos.
- [ ] Implementar devoluções.
- [ ] Implementar consulta de disponibilidade.
- [ ] Implementar relatório de empréstimos.
- [ ] Testar os fluxos principais.
- [ ] Corrigir erros encontrados.
- [ ] Preparar a demonstração final.

### Critérios para considerar uma tarefa concluída
- A funcionalidade está implementada.
- Foi testada com dados de exemplo.
- Os erros encontrados foram corrigidos.
- A equipe conferiu o resultado antes de mover o cartão para **Concluído**.

### Como acompanhar o andamento
- Fazer uma breve reunião para conferir o quadro e combinar prioridades.
- Cada integrante escolhe uma tarefa disponível antes de começar outra.
- Limitar o trabalho em andamento; por exemplo, no máximo 2 tarefas simultâneas por equipe.
- Se tarefas ficarem paradas em **Em teste**, ajudar a concluir os testes antes de iniciar mais atividades.

### Entregas sugeridas
1. Protótipo visual e cadastro de livros/alunos.
2. Empréstimos, devoluções e consulta de disponibilidade.
3. Relatórios, testes e apresentação final.

As entregas são incrementais: cada parte é conferida antes de avançar para a próxima.

## Testes manuais sugeridos
1. Cadastrar um livro com quantidade 2 e um aluno.
2. Registrar empréstimo: a quantidade disponível deve diminuir para 1.
3. Registrar devolução: a quantidade disponível deve voltar para 2.
4. Emprestar todos os exemplares: o livro não deve aparecer como disponível para novo empréstimo.
5. Conferir se o relatório mostra os empréstimos em aberto e devolvidos.

## Evidências para entregar ao professor
- Print do GitHub com os arquivos do projeto.
- Print do GitHub Projects mostrando as colunas e os cartões.
- Print do sistema aberto no navegador.
- Print do cadastro de livro/aluno e de um empréstimo ou relatório.

## Limitações
Este projeto é um protótipo para fins didáticos. Os dados ficam apenas no navegador utilizado e podem ser apagados se o armazenamento local for limpo. Uma versão real precisaria de banco de dados, autenticação, regras de acesso e cópias de segurança.
