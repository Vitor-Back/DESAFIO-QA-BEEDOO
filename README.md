# DESAFIO-QA-BEEDOO

## User Story: Cadastro de curso 
*User Story criada visando o usuário que deseja cadastrar algum curso na plataforma Beedoo, abrangendo todas as validações e campos esperados para essa tela.*

Como usuário do Beedoo QA Chalenge  
Quero cadastrar um curso  
Para que eu possa disponibilizá-lo na listagem de cursos.  

## Casos de teste

1. Tela de cadastro:
    - **DADO** que usuário clique em 'Cadastrar Curso'        
    - **ENTÃO** deve ser direcionado para tela de cadastro de cursos possuindo seus respectivos campos

2. Validação dos campos - Campos obrigatórios:
    - **DADO** que usuário clique em 'Cadastrar Curso' 
    - **MAS** não tenha preenchido nenhum campo 
    - **ENTÃO** os campos obrigatórios devem ser sinalizados  

3.  Validação dos campos - Numero de vagas:
    - **DADO** que usuário preencha o campo numero de vagas 
    - **ENTÃO** campo deve aceitar somente valores numéricos acima de 1

 4. Validação dos campos - Novo campo de Endereço 
    - **DADO** que o usuário tenha selecionado a opção Presencial no drop Tipo curso
    - **ENTÃO** deve ser aberto o campo Endereço no formulário

5. Validação dos campos - Novo campo Link de inscrição  
    - **DADO** que o usuário tenha selecionado a opção Online no drop Tipo curso
    - **ENTÃO** deve ser aberto o campo Link de Inscrição no formulário

6.  Validação dos campos - Campos de da inicial e data final 
    - **DADO** que o usuário tenha informado uma data inicial menor que a data final 
    - **ENTÃO** Campos deve ser sinalizado informando que a data inicial não deve ser maior que a data final

 7. Cadastro de curso:
    - **DADO** que usuário tenha preenchido os campos obrigatórios 
    - **QUANDO** clicado em 'Cadastrar Curso'  
    - **ENTÃO** sistema deve direcionar usuário para tela de listagem dos cursos 
    - **E** informar a mensagem 'Curso cadastrado com sucesso!'


## User Story: Listagem de cursos
*User Story criada visando o usuário que possui cursos cadastrados na plataforma, abrangendo todas as funcionalidades dessa tela.*

Como usuário do Beedoo QA Chalenge  
Quero consultar a listagem de cursos cadastrados  
Para que eu possa excluí-los se necessário  

## Casos de teste

1. Tela listagem:
    - **DADO** que usuário clique em 'Listar Cursos'        
    - **ENTÃO** deve ser direcionado para tela de listagem de cursos possuindo os cursos já cadastrados pelo usuário 

2. Excluir curso:
    - **DADO** que usuário clique na lixeira de um curso listado 
    - **ENTÃO** curso deve se excluído da listagem 
    - **E** apresentar mensagem 'Curso excluído com sucesso!'

## Metodologia 
*Foi utilizada a metodologia do BDD para planejamento e report dos bugs com uso do Gherkin para escrita dos casos de teste*
## Links

1. Planilha de teste - https://l1nk.dev/dBGw2
2. Evidências de teste - https://acesse.one/vtcAf

