# **Projeto**

- A dengue é uma doença febril causada por vírus, caracterizada principalmente por febre alta de início rápido. Dengue é uma palavra espanhola que significa “manha” ou “melindre”, características que o doente costuma apresentar devido ao mal-estar provocado pelos sintomas. Os sintomas normalmente duram até sete dias.

- Segundo o portal de notícias [agênciaBrasil](https://agenciabrasil.ebc.com.br/saude/noticia/2023-12/brasil-e-pais-com-mais-casos-de-dengue-no-mundo-mostra-dados-da-oms), o Brasil lidera o número de casos de dengue no mundo, com **2,9 milhões** de casos registrados somente em 2023, sengundo a Organização Mundial de Saúde (OMS). E o ano de 2024 iniciou com um aumento significativo de casos registrados e de mortes pela doença.

Por isso, é mais do que necessário termos dados e análises concretas de registros de casos, espalhamento da doença e dos seus fatores de incidência.

## **Objetivo**

Fazer uma Análise Exploratória de Dados utilizando um conjunto de dados sobre casos de dengue no Brasil entre os anos 2000 e 2019.

[![Dengue Dataset](casos_dengue_brasil\imagens\dengue_dataset.png)]

## **Conjunto de dados**

[Link para acessar o conjunto de dados](https://www.kaggle.com/datasets/raomuhammadsaeedali/brazil-dengue-dataset-2000-2019/data?select=data_2000_2019.csv)

## **Informações sobre o conjunto de dados**

- O conjunto de dados fornecido compreende uma coleção abrangente de informações relativas a numerosas características geográficas e ambientais em microregiões no Brasil de 2000 a 2019. Códigos e nomes de microregiões, códigos e nomes de mesorregiões, códigos e nomes de estados, códigos e nomes de regiões, códigos e nomes de biomas, códigos e nomes de ecozonas, regimes climáticos, meses, anos, horários, casos de dengue, estimativas populacionais, densidade populacional, temperaturas máximas e mínimas, índice de severidade de seca de Palmer, percentagens de população urbana, percentagens de acesso à rede de água e frequência relatada de escassez de água estão todos incluídos no conjunto de dados. Essas informações estão vinculadas a microregiões individuais e fornecem insights sobre dinâmicas populacionais, padrões climáticos, tendências de urbanização, recursos hídricos e ocorrências de doenças.

## **Metodologia**

Para as análises utilizei dados históricos de casos de dengue e informações climáticas agregadas por estado. As análises incluíram:

- **Análise Temporal**:
  - Avaliação de tendências de longo prazo e padrões sazonais nos dados de casos de dengue.

- **Análise por Região**:
  - Comparação dos casos entre diferentes regiões, identificando áreas com maior incidência da doença.

- **Correlação com Fatores Climáticos**:
  - Investigação da relação entre casos de dengue e fatores climáticos, incluindo temperatura máxima, temperatura mínima, e índice de seca (PDSI).

- **Análise de Correlação:**
  - Gráficos de dispersão e mapa de calor para explorar relações entre casos de dengue e variáveis climáticas.

## **Metadados**

- **micro_name_ibge**: Nome da microrregião, conforme definido pelo Instituto Brasileiro de Geografia e Estatística (IBGE).
- **meso_name**: Nome da mesorregião, uma divisão geográfica que agrupa microrregiões com características sociais e econômicas semelhantes.
- **state_name**: Nome do estado onde os dados foram coletados.
- **region_name**: Nome da região geográfica do Brasil (Norte, Nordeste, Centro-Oeste, Sudeste, Sul) onde os dados foram coletados.
-**biome_name**: Nome do bioma em que a coleta de dados ocorreu, como Amazônia, Cerrado, Caatinga, etc.
- **ecozone_name**: Nome da zona ecológica, que pode se referir a uma classificação mais específica dentro de um bioma ou região.
- **main_climate**: Classificação climática principal da região conforme categorizada.
- **dengue_cases**: Número de casos de dengue registrados na região durante o período de coleta de dados.
-**population**: População total na região durante o período de coleta de dados.
- **pop_density**: Densidade populacional na região (habitantes por quilômetro quadrado).
- **tmax**: Temperatura máxima registrada (possivelmente a média mensal ou anual) na região durante o período de coleta de dados.
- **tmin**: Temperatura mínima registrada (possivelmente a média mensal ou anual) na região durante o período de coleta de dados.
- **pdsi**: Índice de Severidade de Seca de Palmer (Palmer Drought Severity Index), que mede a secura ou umidade relativa do solo.
- **urban**: Porcentagem ou classificação da área considerada urbana na região.
- **water_network**: Indicador da presença ou qualidade da rede de abastecimento de água na região.
- **water_shortage**: Indica se houve escassez de água na região durante o período de coleta de dados.
