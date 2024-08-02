# DESAFIO-QA-BEEDOO

## User Story: Cadastro de curso 
*User Story criada visando o usuário que deseja cadastrar algum curso na plataforma Bedoo, abrangendo todas as validações e campos esperados para essa tela.*

Como usuário do Beedoo QA Chalenge  
Quero cadastrar um curso  
Para que eu possa disponibiliza-lo na listagem de cursos.  

## Casos de teste

1. Tela de cadastro:
    - **DADO** que usuário clique em 'Cadastrar Curso'        
    - **ENTÃO** deve ser direcionadao para tela de cadastro de cursos possuindo seus respectivos campos

2. Validação dos campos - Campos obrigatórios:
    - **DADO** que usuário clque em 'Cadastrar Curso' 
    - **MAS** não tenha preenchido nenhum campo 
    - **ENTÃO** os campos obrigatórios devem ser sinalisados  

3.  Validação dos campos - Numero de vagas:
    - **DADO** que usuário preencha o campo numero de vagas 
    - **ENTÃO** campo deve aceitar somente valores numericos acima de 1
 
 4. Cadastro de curso:
    - **DADO** que usuário tnha preenchido os campos obrigatórios 
    - **QUANDO** clicado em 'Cadastrar Curso'  
    - **ENTÃO** sistema deve direcionar usuário para tela de listagem dos cursos 
    - **E** informar a mensagem 'Curso cadastrado com sucesso!'


## User Story: Listagem de cursos
*User Story criada visando o usuário que possui cursos cadastrados na plataforma, abrangendo todas as funcionalidades dessa tela.*

Como usuário do Beedoo QA Chalenge  
Quero consultar a listagem de cursos cadastrados  
Para que eu possa exclui-los se necessário  

## Casos de teste

1. Tela listagem:
    - **DADO** que usuário clique em 'Listar Cursos'        
    - **ENTÃO** deve ser direcionadao para tela de listagem de cursos possuindo os cursos ja cadastrados pelo usuário 

2. Excluir curso:
    - **DADO** que usuário clque na lixeira de um curso listado 
    - **ENTÃO** curso deve se excluiro da listagem 
    - **E** apresentar mensagem 'Curso excluído com sucesso!'