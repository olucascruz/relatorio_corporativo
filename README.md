# relatorio_corporativo

criação do database disponivel em: https://github.com/julianazanelatto/power_bi_analyst/blob/main/M%C3%B3dulo%203/Desafio%20de%20Projeto/script_bd_company.sql

Transformação de Dados

Renomeação de Colunas

Os nomes das colunas foram alterados para uma melhor compreensão. Por exemplo, "FName" foi modificado para "First_name" e "DName" foi alterado para "Name", uma vez que, estando na tabela de departamentos, já se pode presumir que se refere ao nome do departamento.
Tipo de Dados

O tipo de dados da coluna "Salário" foi alterado para decimal fixo.
Verificação de Valores Nulos

Foi verificado se existiam valores nulos nas colunas e não foram encontrados.
Divisão da Coluna de Endereço

A coluna "Address" foi dividida em quatro novas colunas: "Number Address", "Street Name", "City" e "State".
Mesclagem de Tabelas: Funcionário e Departamento

A tabela "Employee" foi mesclada com a tabela "Department" para incluir o nome do departamento na mesma tabela dos funcionários. A mesclagem foi baseada no código do gerente para identificar a qual departamento cada funcionário pertence.
Mesclagem de Tabelas: Funcionário e Gerente

A tabela "Employee" foi mesclada consigo mesma para incluir o nome do gerente no registro de cada funcionário. A mesclagem foi realizada utilizando o código do gerente.
Agrupamento de Dados

Uma cópia da tabela "Employee" foi criada e a maioria das colunas foi removida, mantendo apenas as colunas de nome do funcionário e nome do gerente. Em seguida, foi utilizada a função 'Agrupar por' para agrupar por nome do gerente, obtendo assim o número de funcionários por gerente.



um relatorio feito durante o bootcamp da DIO
![image](https://github.com/olucascruz/relatorio_corporativo/assets/69447962/0088ade4-8710-4993-ab9a-e4e83d67fd90)
