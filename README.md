# # Sistema de Biblioteca Universitária

PROFITEC – DESENVOLVIMENTO ÁGIL DE SISTEMAS
Sistema de Biblioteca Universitária
Integrantes e Papéis
Product Owner (PO): Gael
Scrum Master: Victor
Developer: Daiana

1. Objetivo do Sistema
Desenvolver um sistema de biblioteca universitária que permita a consulta pública do catálogo sem necessidade de login e o gerenciamento básico do acervo por meio do cadastro e da baixa de exemplares.

2. Product Backlog
US01 – Consultar Catálogo Público Online
Como visitante, quero consultar o catálogo da biblioteca sem login, para encontrar livros disponíveis.
US02 – Pesquisar Obras
Como visitante, quero pesquisar livros por título, autor ou ISBN, para localizar rapidamente uma obra.
US03 – Cadastrar Livros no Acervo
Como bibliotecário, quero cadastrar livros no acervo, para manter o catálogo atualizado.
US04 – Registrar Baixa de Exemplares
Como bibliotecário, quero registrar a baixa de exemplares perdidos ou danificados, para manter o acervo correto.
US05 – Visualizar Detalhes de uma Obra
Como visitante, quero visualizar os detalhes de uma obra, para obter mais informações sobre o livro.
US06 – Editar Informações de um Livro
Como bibliotecário, quero editar informações de um livro cadastrado, para corrigir dados do acervo.
US07 – Filtrar Livros por Autor
Como visitante, quero filtrar livros por autor, para encontrar obras mais rapidamente.
US08 – Visualizar Apenas Livros Disponíveis
Como visitante, quero visualizar apenas os livros disponíveis, para facilitar a busca.

3. Critérios de Aceite
US01 – Consultar Catálogo Público Online
O catálogo deve estar acessível sem necessidade de autenticação.
O sistema deve exibir uma lista de livros cadastrados.
Cada livro deve apresentar título, autor e disponibilidade.
O catálogo deve carregar corretamente na página inicial.
Caso não existam livros cadastrados, deve ser exibida uma mensagem informativa.
US02 – Pesquisar Obras
Permitir pesquisa por título.
Permitir pesquisa por autor.
Permitir pesquisa por ISBN.
Exibir apenas os resultados compatíveis.
Exibir mensagem quando não houver resultados.
Não exigir login.
US03 – Cadastrar Livros no Acervo
Permitir cadastro de título, autor, ISBN, editora, ano de publicação e quantidade.
Validar campos obrigatórios.
Não permitir ISBN duplicado.
Exibir mensagem de confirmação.
Atualizar o catálogo após o cadastro.
US04 – Registrar Baixa de Exemplares
Permitir selecionar o livro.
Exigir o motivo da baixa.
Atualizar automaticamente a quantidade disponível.
Não permitir baixa superior à quantidade existente.
Registrar data e motivo da baixa.
Exibir confirmação da operação.

4. Priorização MoSCoW
Must Have
US01 – Consultar Catálogo Público Online
US02 – Pesquisar Obras
US03 – Cadastrar Livros no Acervo
US04 – Registrar Baixa de Exemplares
Should Have
US05 – Visualizar Detalhes de uma Obra
US06 – Editar Informações de um Livro
Could Have
US07 – Filtrar Livros por Autor
US08 – Visualizar Apenas Livros Disponíveis
Won't Have
Cadastro de usuários
Sistema de login
Reserva de livros
Histórico de empréstimos
Integração com sistemas externos
Sugestão inteligente de obras

5. Meta do Sprint 1
Ao final do Sprint 1, a equipe deverá apresentar um sistema capaz de disponibilizar o catálogo público da biblioteca para consulta sem necessidade de login, permitindo aos visitantes visualizar e pesquisar obras cadastradas, além de possibilitar aos bibliotecários realizar o cadastro e a baixa de exemplares, garantindo o gerenciamento básico e a atualização do acervo.

6. Sprint Backlog
US01 – Consultar Catálogo Público
Backend
Definir entidade Livro.
Modelar o banco de dados.
Criar a listagem dos livros.
Definir a regra de disponibilidade.
Frontend
Criar a tela do catálogo.
Exibir os livros cadastrados.
Exibir a disponibilidade de cada livro.
Exibir mensagem quando não houver livros cadastrados.

US02 – Pesquisar Obras
Backend
Implementar busca por título.
Implementar busca por autor.
Implementar busca por ISBN.
Tratar pesquisas sem resultados.
Frontend
Criar campo de pesquisa.
Criar botão de pesquisa.
Exibir os resultados encontrados.
Exibir mensagem quando nenhum livro for encontrado.

US03 – Cadastrar Livros
Backend
Validar os campos obrigatórios.
Validar ISBN duplicado.
Criar a lógica de cadastro.
Salvar as informações do livro.
Frontend
Criar formulário de cadastro.
Criar campos de entrada.
Exibir mensagens de erro.
Exibir mensagem de sucesso após o cadastro.

US04 – Registrar Baixa de Exemplares
Backend
Validar quantidade disponível.
Atualizar a quantidade do acervo.
Registrar o motivo da baixa.
Registrar a data da baixa.
Frontend
Criar tela de baixa.
Criar seleção do livro.
Criar campo para informar o motivo.
Exibir mensagem de confirmação.

7. Organização do Trello
O quadro do Trello foi organizado nas seguintes listas:
Informações do Projeto
Product Backlog
Sprint 1 Backlog
Em Andamento
Em Revisão
Concluído
Documentação
Na lista Informações do Projeto foram adicionados os cartões contendo o objetivo do sistema, os integrantes da equipe e a meta do Sprint 1.
Na lista Product Backlog foram cadastradas as oito User Stories definidas pela equipe.
Na lista Sprint 1 Backlog foram adicionadas as quatro histórias priorizadas (Must Have), que serão desenvolvidas no primeiro Sprint.
Na lista Documentação foram registrados os critérios de aceite, a priorização MoSCoW, a definição da equipe, o objetivo do projeto e a meta do Sprint 1.
As listas Em Andamento, Em Revisão e Concluído serão utilizadas para acompanhar o progresso das atividades durante a execução do Sprint.

8. Conclusão
A equipe concluiu a definição dos papéis, a elaboração do Product Backlog com oito User Stories, os critérios de aceite das quatro principais histórias, a priorização utilizando a técnica MoSCoW, a definição da Meta do Sprint 1, a construção do Sprint Backlog e a organização do quadro no Trello.
Todo o planejamento foi realizado seguindo os princípios do Scrum e do Desenvolvimento Ágil de Sistemas, preparando a equipe para a execução do MVP do Sistema de Biblioteca Universitária durante os próximos sprints.