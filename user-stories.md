# User Stories para o Módulo de Cadastro de Curso

## 1. Cadastro de Curso
**Como** um administrador,  
**Eu quero** preencher todos os campos do formulário de cadastro de curso e clicar em "Cadastrar Curso",  
**Para que** o curso seja cadastrado com sucesso e apareça na lista de cursos.

## 2. Validação de Campos Obrigatórios
**Como** um administrador,  
**Eu quero** preencher o formulário de cadastro de curso sem completar todos os campos obrigatórios e clicar em "Cadastrar Curso",  
**Para que** uma mensagem de erro seja exibida, informando que todos os campos obrigatórios precisam ser preenchidos.

## 3. Exibição Condicional de Campos
**Como** um administrador,  
**Eu quero** selecionar o tipo de curso (Presencial ou Online),  
**Para que** o formulário exiba campos adicionais apropriados, como "Endereço" para Presencial e "Link de inscrição" para Online.

## 4. Validação de Datas e URL
**Como** um administrador,  
**Eu quero** preencher as datas de início e fim, e a URL da imagem da capa,  
**Para que** o sistema valide se a data final é maior que a data inicial e se a URL da imagem é válida, exibindo mensagens de erro apropriadas quando necessário.

## 5. Validação de Número de Vagas e Tipo de Curso
**Como** um administrador,  
**Eu quero** preencher o campo "Número de vagas" com um valor positivo e numérico e selecionar um tipo de curso,  
**Para que** o sistema valide se o valor é positivo e numérico e se o tipo de curso foi selecionado, exibindo mensagens de erro quando necessário.

## 6. Visualização e Exclusão de Cursos
**Como** um usuário,  
**Eu quero** ver a lista de cursos cadastrados em formato de cards na página de listagem e ter a opção de excluir um curso,  
**Para que** eu possa visualizar e gerenciar os cursos listados.
