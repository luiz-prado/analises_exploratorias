# **Casos de Dengue no Brasil | 2000 a 2019**

- A dengue é uma doença febril causada por vírus, caracterizada principalmente por febre alta de início rápido. Dengue é uma palavra espanhola que significa “manha” ou “melindre”, características que o doente costuma apresentar devido ao mal-estar provocado pelos sintomas. Os sintomas normalmente duram até sete dias.

- Segundo o portal de notícias [Agência Brasil](https://agenciabrasil.ebc.com.br/saude/noticia/2023-12/brasil-e-pais-com-mais-casos-de-dengue-no-mundo-mostra-dados-da-oms), o Brasil lidera o número de casos de dengue no mundo, com **2,9 milhões** de casos registrados somente em 2023, sengundo a Organização Mundial de Saúde (OMS). E o ano de 2024 iniciou com um aumento significativo de casos registrados e de mortes pela doença.

- Com isso, é mais do que necessário termos dados e análises concretas de registros de casos, espalhamento da doença e dos seus fatores de incidência.

## **Objetivo**

Realizar uma Análise Exploratória de Dados utilizando um conjunto de dados sobre casos de dengue no Brasil entre os anos 2000 e 2019.

## **Conjunto de dados**

![Casos Dengue](https://github.com/luiz-prado/analises_exploratorias/blob/a447b5ee44998d0191773fd541e61573c8ea71ad/casos_dengue_brasil/imagens/dengue_dataset.png)
[Link para acessar o conjunto de dados](https://www.kaggle.com/datasets/raomuhammadsaeedali/brazil-dengue-dataset-2000-2019/data?select=data_2000_2019.csv)

## **Informações sobre o conjunto de dados**

- O conjunto de dados fornecido compreende uma coleção abrangente de informações relativas a numerosas características geográficas e ambientais em microregiões no Brasil de 2000 a 2019. Essas informações estão vinculadas a microregiões individuais e fornecem insights sobre dinâmicas populacionais, padrões climáticos, tendências de urbanização, recursos hídricos e ocorrências de doenças.

## **Metadados**

- *micro_code*: Unique ID number given by IBGE to each microregion (5 digits)
- *micro_name*: Name of each microregion
- *micro_name_ibge*: Name of each microregion (from IBGE sources)
- *meso_code*: Unique ID number given by IBGE to each mesoregion (4 digits)
- *meso_name*: Name of each mesoregion
- *state_code*: Unique ID number given by IBGE to each state
- *state_name*: Name of state
- *region_code*: Region code
- *region_name*: Region name
- *biome_code*: Biome code
- *biome_name*: Biome name
- *ecozone_code*: Ecozone code (same as biome apart from Atlantic Rainforest, biome code 6, which has been separated into NE Atlantic rainforest, ecozone code 6, SE Atlantic Rainforest, ecozone code 7, and S Alantic Rainforest, ecozone code 8)
- *ecozone_name*: Ecozone name (same as biome apart from Atlantic Rainforest, which has been separated into NE Atlantic rainforest, SE Atlantic Rainforest, and S Alantic Rainforest)
- *main_climate*: Most prevalent climate regime in the microregion. Based on Koppen Geiger climate regimes
- *month*: Calendar month index, 1 = January, É, 12 = December
- *year*: Year 2000 - 2019
- *time*: Time index starting at 1 for January 2000
- *dengue_cases*: Number of notified dengue cases registered in the notifiable diseases system in Brazil (SINAN) in the microregion of reference, at the month of first symptoms
- *population*: Estimated population, based on projections calculated using the 2000 and 2010 censuses, and counts carried out in 2007 and 2017
- *pop_density*: Population density (number of people per km2)
- *tmax*: Monthly average daily maximum temperature; gridded values (at a 0.5¡ resolution) averaged across each microregion using the 'exactextratr' R package (¡C)
- *tmin*: Monthly average daily minimum temperature; gridded values (at a 0.5¡ resolution) averaged across each microregion using the 'exactextratr' R package (¡C)
- *pdsi*: Self-calibrated Palmer drought severity index for each microregion (a measure of how wet or dry a region is relative to usual conditions). Negative values represent periods of drought, positive values represent wetter periods. Calculated by taking the mean value within each microregion using the exact_extract R package
- *urban*: Percentage of inhabitants living in urban areas according to the 2010 census
- *water_network*: Percentage of inhabitants with access to the piped water network according to the 2010 census
- *water_shortage*: Frequency of reported water shortages per microregion between 2000 - 2016

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

## **Conclusão**

- Ao longo deste projeto, exploramos a distribuição e os fatores associados aos casos de dengue no Brasil, no período de 2000 a 2019, utilizando um conjunto de dados que inclui informações sobre os casos de dengue e variáveis climáticas por estado. Através de análises gráficas e estatísticas, identificamos padrões e correlações que oferecem insights sobre como o clima pode influenciar a transmissão da dengue no país.

- A análise gráfica revelou variações na incidência da dengue ao longo do tempo e entre diferentes regiões geográficas. Gráficos de dispersão entre casos de dengue e variáveis climáticas como temperatura média e escassez de água forneceram uma visão inicial da complexa interação entre o clima e a transmissão da dengue. Embora algumas relações não tenham mostrado padrões claros, observamos que certas condições climáticas podem estar associadas a um aumento no número de casos de dengue.

- Concluímos que, embora existam correlações entre os casos de dengue e fatores climáticos, a transmissão da doença é influenciada por uma combinação complexa de fatores, incluindo variáveis ambientais, sociais e de saúde pública. Portanto, estratégias eficazes de prevenção e controle da dengue no Brasil devem considerar essa multifatorialidade, adaptando-se às condições locais específicas de cada região.
