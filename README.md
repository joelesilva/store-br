# Análise de Dados das Lojas

Este projeto consiste em uma análise exploratória dos dados de vendas de quatro lojas. Foram utilizadas bibliotecas como **Pandas**, **Matplotlib** e **Seaborn** para realizar o carregamento, manipulação e visualização dos dados. O objetivo é identificar padrões de faturamento, popularidade de categorias de produtos, avaliações dos clientes, custo do frete e distribuição geográfica das vendas.

## Funcionalidades

- **Faturamento Total:** Cálculo do faturamento de cada loja a partir do valor das vendas.
- **Vendas por Categoria:** Contagem dos produtos vendidos por categoria em cada loja.
- **Média de Avaliações:** Cálculo da média das avaliações dos clientes para identificar a satisfação.
- **Produtos Mais e Menos Vendidos:** Identificação dos produtos com maior e menor quantidade de vendas em cada loja.
- **Custo Médio de Frete:** Análise do gasto médio com frete em cada loja.
- **Visualizações Geográficas:** Criação de gráficos de dispersão e heatmaps para mapear a distribuição das vendas com base nas coordenadas geográficas.
- **Gráfico Unificado de Dispersão:** Visualização de todas as lojas em um único gráfico, diferenciando-as por cor.

## Dependências

Certifique-se de ter as seguintes bibliotecas:
- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)

Você pode instalar as dependências utilizando `pip`:

```bash
!pip install pandas matplotlib seaborn
```

## Instalação e Execução

- Clone o repositório:

```bash
git clone https://github.com/joelesilva/store-br.git
cd store-br
```

- Abra o projeto no Google Colab ou em sua IDE local:
Caso utilize o Colab, basta fazer o upload do arquivo .ipynb e executar as células.
Caso preferir rodar localmente, utilize o Jupyter Notebook ou outro ambiente Python de sua preferência.

## Organização dos Arquivos

- AluraStoreBr.ipynb: Notebook contendo o código completo para a análise dos dados e geração dos gráficos.
- README.md: Este arquivo de documentação.
- Outros arquivos adicionais ou dados podem ser adicionados conforme necessário.

## Possíveis Problemas e Soluções

- Erro ao carregar colunas: Certifique-se de que os nomes das colunas do CSV correspondem exatamente aos utilizados no código (ex.: "Preço", "Frete", etc.).
- Problemas com dependências: Verifique se todas as bibliotecas necessárias estão instaladas e atualizadas.

## Considerações Finais

Este projeto foi desenvolvido com o intuito de demonstrar habilidades em análise de dados e visualização utilizando Python. Sinta-se à vontade para explorar, modificar e adaptar o código conforme necessário.

