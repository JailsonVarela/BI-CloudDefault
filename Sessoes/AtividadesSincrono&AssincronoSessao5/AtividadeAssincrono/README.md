# Laboratório Assíncrono — OA5
## Modelação e Análise Temporal no Power BI

### Atividade 05

**Contexto do Exercício**: A empresa "LusaTech" registou as suas vendas ao longo do último ano numa tabela simples, mas o departamento de análise precisa de explorar esses dados ao longo do tempo (por ano, trimestre e mês) e perceber as margens de lucro. O modelo atual não tem uma dimensão de tempo adequada, nem os cálculos de rentabilidade fechados.

O teu objetivo é construir uma Tabela de Datas de raiz e criar as colunas necessárias para a análise financeira. 

#### Parte 1: Criação do relatório e importação de dados.
* Crie um novo ficheiro de Power BI e guarde com o seu nome e data de hoje. (NomeApelido_dd-mm-yyyy.pbix)
* Importe a tabela Vendas: Contém as colunas Data da Venda, ID Produto, Quantidade Vendida, Custo Unitário e Preço Unitário.  
Utilize a ligação Web para aceder aos dados de uma Googlesheet publica. Não é necessário fazer qualquer tipo de login. 
    **Link para uma Googlesheet**: 
    https://docs.google.com/spreadsheets/d/1Xqjoskhl9tcghJZVNbfimLmvSu4HogFuyAw9O3oOP5M/export?format=csv

No Power Query: 
* Altere o nome da tabela para Vendas 
* Confirme o tipo de dados e carregue para o Desktop. 


#### Parte 2: Criação da Tabela de Datas (De raiz) 
Para que o modelo possa ser filtrado temporalmente de forma correta, não deves 
usar as hierarquias automáticas do Power BI. 
1. Cria uma tabela no Power BI chamada Calendario utilizando DAX 
(sugestão: explora as funções CALENDAR ou CALENDARAUTO). 
2. Garante que o intervalo de datas gerado cobre, pelo menos, de 1 de janeiro 
do ano passado até 31 de dezembro do ano atual. 
3. Altera o tipo de dados para só data. Formata como quiseres. 
4. **? Define esta nova tabela como a "Tabela de Dados" (Mark as Date Table) nas 
configurações do Power BI.** 


#### Parte 3: Enriquecer a Tabela de Datas (Colunas Calculadas) 
Abre a vista de dados da tua nova tabela Calendario e cria as seguintes colunas 
calculadas usando DAX: 
1. Ano: O ano da data correspondente. 
2. Mês Num: O número do mês (1 a 12). 
3. Mês Nome: A abreviatura do mês em Português (ex: Jan, Fev, Mar). 
4. Trimestre: O trimestre do ano, formatado como "T1", "T2", etc. 
5. Ordene a coluna com o nome dos meses pela coluna numérica 
correspondente. 

#### Parte 4: Cálculos Financeiros na Tabela de Factos (Colunas Calculadas) 
Na tabela Vendas, precisamos de apurar os valores totais de cada transação. Cria 
as seguintes colunas calculadas: 
1. Custo Total: Multiplicação da quantidade pelo custo unitário. 
2. Faturação Total: Multiplicação da quantidade pelo preço unitário. 
3. Margem de Lucro: A diferença entre a Faturação Total e o Custo Total. 


#### Parte 5: Relacionamento e Teste 
1. Na vista de Modelo, cria o relacionamento adequado entre a tabela 
Calendario e a tabela Vendas. 
2. Cria um gráfico de colunas simples que mostre a Faturação Total por Ano 
e Trimestre para comprovares que o teu modelo funciona na perfeição. 
3. **? Ordene o gráfico pela dimensão temporal.** 
4. Altera o nome da folha para Faturação.

As tranformaçoes mencionadas acima foram aplicadas no power BI e o relatório criado foi:
* Gráfico de colunas simples que mostre a Faturação Total por Ano e Trimestre.
![Relatorio Final](./evidencias/Captura%20de%20ecrã%202026-10-20%20123205.png)

![Exemplo de criação de coluna calculada](./evidencias/Captura%20de%20ecrã%202026-10-20%20121924.png)

As evidências podem ser encontradas na [**pasta evidências**](./evidencias/)
 

