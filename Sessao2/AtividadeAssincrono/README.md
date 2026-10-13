# Laboratório Assíncrono — OA2
## Principais ferramentas de transformação e limpeza de dados.
## Utilizar o processo Append Queries.

### Atividade 02 - Append Queries

#### Parte 1: Criação do relatório e importação de dados.
* Crie um novo ficheiro de Power BI e guarde com o seu nome e data 
de hoje. (NomeApelido_dd-mm-yyyy.pbix)
* Importe os dados de todas as folhas do ficheiro de Excel em anexo 
([All data by Month.xlsx](./All%20data%20by%20Month.xlsx))

#### Parte 2: Transformação dos dados no Power Query
1. Aplique o processo de Append Queries para juntar as 12 folhas 
numa só tabela.
2. Aplique todas as transformações que ache necessárias.


As transformações que executei foram:
1. Juntar todas as folhas de excel numa só tabela;
2. Eliminar as colunas de "CodConta", "CodCentroCusto", "CodFilial";
3. Criar uma coluna CodFilial.1 com o ultimo digito de CodFilial;
4. Mudar o tipo de dados da coluna "DataMovimento" para Data;
5. Desmarcar opção de "Ativar carregamento"nas tabelas que não são necessárias para o relatório;
6. Verificar se os cabeçalhos foram excluidos do corpo dos dados;
7. Renomear TipoMovimento "D" e "C" para "Débito" e "Crédito";
8. Mudar o tipo de dados de "Valor" com região para número decimal, região Inglês (EUA);
9. Confirmar o numero de linhas importadas no Power Query e no Power BI Desktop

#### Parte 3: Criação do relatório no Power BI Desktop
1. Crie um cartão com o total do campo valor.
2. Crie um gráfico de linhas que mostre como evolui o valor ao longo 
do ano

Os relatórios criados foram:
* Um cartão com o total do campo valor
* Um gráfico de linhas que mostra como evolui o valor ao longo do ano

Pontos de melhoria:
- Guardar o ficheiro como primeiro passo depois de criar o projecto novo
- Desmarcar opção de "Ativar carregamento" nas tabelas que não são necessárias para o relatório

As evidências podem ser encontradas na [**pasta evidências**](./evidencias/)