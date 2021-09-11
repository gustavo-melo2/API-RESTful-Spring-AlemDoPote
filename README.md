# API RESTful Spring do projeto Além Do Pote
Nome do grupo: YoungDevs

Turma: 2TDSA

Challenge Sprint 3

1. Justificativa do Projeto

Há uma situação por qual a maior parte das pessoas já passaram, começar a
preparar algum alimento e se deparar com a falta de algum dos ingredientes
essenciais, como açúcar, sal ou o tão apreciado café.
Para resolver este problema criamos um dispositivo IOT inovador, o Além do
Pote é capaz de monitorar o conteúdo do recipiente e alertar o usuário quando deve
reabastecê-lo. Além de poder acompanhar a quantidade de consumo deste
ingrediente pela família, conscientizando o usuário de possíveis risco para saúde.

2. Finalidade do Projeto

Desenvolver potes inteligentes para auxiliar o usuário em suas compras e
saúde.

3. Objetivo(s) do Projeto

• Identificar possíveis riscos de consumo excessivo de produtos da família
• Facilitar o controle de quantidades de produtos que o usuário possui

4. Descrição do Produto

O dispositivo servirá como um pote e irá monitorar o conteúdo deste por um
sensor de peso, mandando dados (os quais serão armazenados virtualmente) para o
aplicativo, que poderá mandar alertas ao usuário quando algo estiver acabando e
preparar um relatório mensal do consumo total, comparando com a quantia ideal
para saúde.

5. Arquitetura da Solução

![MicrosoftTeams-image (8)](https://user-images.githubusercontent.com/63134386/132961502-49aa8869-f725-4eeb-b089-6a9a7431d697.png)

6. Tabela dos endpoints

Usuario

![endpointUsuario](https://user-images.githubusercontent.com/63134386/132961683-eb9e9a5d-2892-4dd6-a9f9-a817d2d75bae.png)

Pote

![endpointPote](https://user-images.githubusercontent.com/63134386/132961709-af7eaed3-525d-4ee2-9100-cc86f0455348.png)

Relatorio

![endpointsRelatorio](https://user-images.githubusercontent.com/63134386/132961704-ec5be207-c8d3-431a-b827-94ed1b33f461.png)

7. Descrição das funcionalidades do backend

O backend do nosso sistema terá como funcionalidades o cadastro, edição, consulta e exclusão de dados das nossas tabelas no banco de dados. Além também de cálculos de como estão os consumos dos alimentos armazenados nos potes.

Foi implementada a parte da API RESTful responsável por cadastrar e gerenciar os registros dos nossos Pote no banco de dados. 

