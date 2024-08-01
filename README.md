# DESAFIO-BEEDOO

Link para acesso a planilha com os casos de teste e artefatos criados com as evidencias de erros criados:
<https://drive.google.com/drive/folders/12jJx4P1qKZF1GYUCLnufqXkl82S_henC?usp=sharing>

## Etapa 1

### User Story

Para criar a história de usuário, primeiramente foi analisado os dados disponíveis da aplicação e o objetivo final do cliente. Compreendemos quais são as funcionalidades mais importantes e como podemos proporcionar a melhor experiência para nossos usuários.

---

**US-1: Cadastro de Curso**

**Como** um usuário registrado,
**Eu quero** cadastrar um curso informando o nome do curso, sua descrição, nome do instrutor, link com a imagem de capa do curso, data de início e finalização do curso, número de vagas e o tipo do curso (online ou presencial),
**Para que** eu possa adicionar novos cursos à plataforma e disponibilizá-los para os alunos.

**Critérios de Aceitação:**
1. O usuário deve acessar a funcionalidade de cadastro de cursos a partir da interface principal.
2. O formulário de cadastro deve conter campos obrigatórios para o nome do curso, descrição, nome do instrutor, link da imagem de capa, data de início, data de finalização, número de vagas e tipo de curso.
3. A data de início deve ser anterior à data de finalização.
4. O curso deve ser salvo no banco de dados e estar disponível para visualização na lista de cursos do usuário.
5. O usuário deve receber uma confirmação visual de que o curso foi cadastrado com sucesso.

---

**US-2: Adição de Curso à Lista**

**Como** um usuário registrado,
**Eu quero** que, ao cadastrar um novo curso, ele seja automaticamente adicionado à lista de cursos que criei,
**Para que** eu possa visualizar todos os cursos que cadastrei em um só lugar.

**Critérios de Aceitação:**
1. Após o cadastro de um novo curso, ele deve ser imediatamente adicionado à lista de cursos do usuário.
2. A lista de cursos deve ser atualizada em tempo real sem a necessidade de recarregar a página.
3. O novo curso deve aparecer na lista com todas as informações básicas: nome, data de início, data de finalização e número de vagas.

---

**US-3: Flexibilidade de Datas de Cursos**

**Como** um usuário registrado,
**Eu quero** poder selecionar tanto longos intervalos de tempo quanto curtos entre as datas de início e finalização de um curso,
**Para que** eu possa ter flexibilidade no planejamento dos cursos oferecidos.

**Critérios de Aceitação:**
1. O formulário de cadastro de curso deve permitir a seleção de qualquer intervalo de tempo entre a data de início e a data de finalização.
2. Não deve haver restrições mínimas ou máximas para o intervalo de tempo entre as duas datas, exceto que a data de início deve ser anterior à data de finalização.

---

**US-4: Visualização de Informações dos Cursos**

**Como** um usuário registrado,
**Eu quero** acessar a lista de cursos e visualizar o nome do curso, datas de início e finalização, e a quantidade de vagas disponíveis,
**Para que** eu possa ter uma visão rápida e clara das informações principais de cada curso.

**Critérios de Aceitação:**
1. A lista de cursos deve exibir o nome do curso, data de início, data de finalização e o número de vagas disponíveis para cada curso.
2. As informações devem ser apresentadas de forma clara e organizada.
3. O usuário deve poder ordenar ou filtrar a lista de cursos por qualquer uma dessas informações.

---

**US-5: Exclusão de Cursos**

**Como** um usuário registrado,
**Eu quero** poder excluir um curso quando ele acabar ou caso ele não esteja mais ativo,
**Para que** eu possa manter minha lista de cursos atualizada e livre de cursos obsoletos.

**Critérios de Aceitação:**
1. O usuário deve ter a opção de excluir qualquer curso da lista de cursos.
2. Antes da exclusão, deve ser exibida uma mensagem de confirmação para evitar exclusões acidentais.
3. Após a exclusão, o curso deve ser removido permanentemente do banco de dados e da lista de cursos do usuário.
4. O usuário deve receber uma confirmação visual de que o curso foi excluído com sucesso.

---
### Cenarios de teste

