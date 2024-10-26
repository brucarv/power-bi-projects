# Relatório de Transformação dos Dados

## Alterações Realizadas ao db company.mysql

- **Alteração do Tipo de Dados - Coluna Salary**
  - Alterei os valores da coluna `Salary` na tabela `employee` de inteiros para *double*, a fim de lidar com valores decimais.

- **Transformação de Dados - Coluna Hours**
  - Transformei os dados da coluna `Hours` da tabela `works_on` para inteiros, visando melhorar a visualização dos dados.

- **Separação da Coluna Address**
  - Separei a coluna `Address` em diferentes colunas (`no`, `place`, `city`, `state`) para reduzir a complexidade de exibição do endereço.

- **Mescla de Nome e Sobrenome**
  - Mesclei as colunas de **Nome** e **Sobrenome** em uma única coluna, consolidando o nome completo dos colaboradores.

- **Mescla de Departamento e Localização**
  - Mesclei os nomes de **departamentos** e **localização** para garantir que cada combinação departamento-local seja única.

## Racionalização das Decisões

- A opção **"Mesclar"** foi escolhida em vez de **"Atribuir"** para combinar informações específicas de duas tabelas distintas, reunindo dados do departamento e suas respectivas localizações. Esta junção permite uma visualização e análise unificadas, consolidando as informações relevantes em uma linha.
