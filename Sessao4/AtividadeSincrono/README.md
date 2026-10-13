# Laboratório Síncrono — OA4
## Modelo de dados relacional - Boas práticas

### Atividade 04
Nesta atividade utilizamos os arquivos que se encontram na pasta [modelo](./Modelo/) importando os seguintes ficheiros:
* [fSales](./Modelo/fSales.xlsx) <-- Ficheiro de Excel com os dados de vendas
* [dProduct](./Modelo/dProducts.xml) <-- Ficheiro de XML com os dados dos produtos
* [dSubCategories](./Modelo/dSubCategories.txt) <-- Ficheiro de texto com as subcategorias
* [dStores+dLocations](./Modelo/dStores+dLocations.xlsx) <-- Ficheiro de Excel com as lojas e localizações

O objetivo desta atividade é observar as relações entre as tabelas e perceber a sua estrutura.
Também criamos relatórios com informações extraidas das diferentes tabelas e mapas da distribuição das lojas por paises e continentes.

As evidências podem ser encontradas na [**pasta evidências**](./evidencias/)

Os relatórios criados foram:
- Mapa da distribuição das lojas por paises
- Mapa de dispersão com a distribuição das lojas por continentes

![](./evidencias/Captura%20de%20ecrã%202026-10-13%20222332.png)

- Cartão com o total de vendas
- Tabela com o total de vendas pelo nome do produto
- Treemap com total de vendas pelo nome da marca
- Gráfico de barras agrupadas com o total de vendas por subcategoria

![](./evidencias/Captura%20de%20ecrã%202026-10-13%20230526.png)


Dicas:
- Sempre que aparecer uma table no espaço de uma tabela não devemos clicar nala, clicamos ao lado para visualizar o conteudo nos detalhes.
- Nomes dos atributos que são os nomes das colunas devem ter um nome mais natural. 
- Podemos ocultar o campo ProductKey na tabela Sales que deixa de estar visivel na tabela de vistas do relatório. 
Ou por outras palavras podemos ocultar as chaves estrangeiras na vista do modelo para uma melhor visualização e compreensão dos dados na vista de relatório.
