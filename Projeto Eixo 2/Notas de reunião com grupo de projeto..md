## Membros do grupo
* Edmar Nunes da Silva
* Gabriel Lopes Menezes
* Jordan Machado Câmara
* Luiz Henrique Soares Santos
* Pedro Ferreira
* Thiago Jorge de Sousa

### Reunião Quinta 15/08/2024, 19:30

Reunião iniciada, foi pedido para que fizéssemos uma recapitulação das orientações do projeto. Basicamente, temos que criar uma arquitetura de banco de dados baseado num problema, a orientadora nos disponibilizou o [[Material de apoio (Modelo de projeto)]] onde se encontra uma arquitetura de banco de dados de uma escola. 

Em seguida, foi discutido qual seria o tema. Jordan sugeriu que montássemos uma arquitetura de banco de dados que fosse útil para alguém, um tema nos possibilitaria vender o projeto quando finalizado. Ele deu de exemplo uma loja/oficina de conserto de bicicleta, que também venderia peças e outras coisas relacionadas ao esporte, onde haveria uma função de agendamentos. 

Outros membros manifestaram que Pedro tem 7 anos de experiência vendendo sistemas para varejistas de diversos ramos. O tema foi escolhido, um banco de dados que pode ser integrado ou ser parte de um sistema de loja de varejo. A ideia sobre uma loja/oficina foi descartada, não haverá função de agendamentos. 

Foi comentado que precisamos escolher uma "empresa fictícia" como a escola. O tema "loja de varejo" é muito generalista e precisamos escolher qual é o ramo da empresa. Também vale salientar que até o momento da reunião somente um integrante leu o modelo de projeto, portanto, é compreensível que o tema ainda esteja generalizado.

Foi muito discutido como será o projeto, até a parte de requisitos, que será feita somente na etapa 2. O Thiago criou um esboço de algumas funções:

"Desenvolvimento de uma pipeline de dados com foco em vendas de produtos e emissão de NF.

O sistema é responsável por gerenciar estoque, calcular o somatório de comissão de cada funcionário, baseado no faturamento e modelo de pagamento, também emitir NF descrevendo os produtos vendidos, modelo de pagamento, valor do produto distinto e também somatório total.

Também é possível que o sistema armazene informações dos clientes, mas são informações opcionais."

O Pedro discordou que precisamos ter a função de emissão de NF (nota fiscal) e decidimos esperar uma opinião da orientadora na próxima [Reunião Quinta 22/08/2024, 19:30]. Ele também contribuiu com um esboço das entidades que estarão presentes na arquitetura:

Clientes
Localidades
Produtos
Modalidades
Operadora
Funcionários
Vendas
Itens vendas
A receber
Recebimentos

Foi finalizada a reunião.


