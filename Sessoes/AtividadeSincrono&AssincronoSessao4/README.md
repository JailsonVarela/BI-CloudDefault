# Laboratório Síncrono — OA4
## Modelo de dados relacional - Boas práticas

### Atividade 04
#### Sincrono
Nesta atividade utilizamos as tabelas dos ficheiros que se encontram na pasta [modelo](../Modelo/) para importar dados:
* [fSales](../Modelo/fSales.xlsx) <-- Ficheiro de Excel com a tabela de vendas
* [dProduct](../Modelo/dProducts.xml) <-- Ficheiro de XML com a tabela de produtos
* [dSubCategories](../Modelo/dSubCategories.txt) <-- Ficheiro de texto com a tabela de subcategorias
* [dStores+dLocations](../Modelo/dStores+dLocations.xlsx) <-- Ficheiro de Excel com as tabelas de lojas e localizações

#### Assincrono
Adicionamos mais uma tabela do ficheiro abaixo à pasta modelo: 
* [dCategories](../Modelo/dCategories.xlsx) <-- Ficheiro de Excel com a tabela de categorias

#### Objetivo Comum
O objetivo desta atividade é observar as relações entre as tabelas e perceber a sua estrutura.
Também criamos relatórios com informações extraidas das diferentes tabelas e mapas da distribuição das lojas por paises e continentes.

Para a Atividade Assíncrona adicionamos uma nova pagina ao relatório, alterando o seu nome para categories.

#### Evidências
As evidências podem ser encontradas nas pastas [**evidenciasSincrono**](./evidenciasSincrono/) e [**evidenciasAssincrono**](./evidenciasAssincrono/)

Os relatórios criados foram:
- Mapa da distribuição das lojas por paises
- Mapa de dispersão com a distribuição das lojas por continentes

![](./evidenciasSincrono/Captura%20de%20ecrã%202026-10-13%20222332.png)

- Cartão com o total de vendas
- Tabela com o total de vendas pelo nome do produto
- Treemap com total de vendas pelo nome da marca
- Gráfico de barras agrupadas com o total de vendas por subcategoria

![](./evidenciasSincrono/Captura%20de%20ecrã%202026-10-13%20230526.png)

- Gráfico de barras com o total de vendas (SalesAmount) por Categoria
- Slicer (segmentação de dados) por BrandName da tabela Products.

![](./evidenciasAssincrono/Captura%20de%20ecrã%202026-10-14%20123946.png)

Dicas:
- Sempre que aparecer uma table no espaço de uma tabela não devemos clicar nala, clicamos ao lado para visualizar o conteudo nos detalhes.
- Nomes dos atributos que são os nomes das colunas devem ter um nome mais natural. 
- Podemos ocultar o campo ProductKey na tabela Sales que deixa de estar visivel na tabela de vistas do relatório. 
Ou por outras palavras podemos ocultar as chaves estrangeiras na vista do modelo para uma melhor visualização e compreensão dos dados na vista de relatório.


Para analisar esta versão deve mover o ficheiro [Modelo 13-10-2026.pbix](./Modelo%2013-10-2026.pbix) para a [pasta diretamente acima](./../) (\Modulo05BI&CloudDefault\Sessoes) e então abrir no Power BI Desktop. 