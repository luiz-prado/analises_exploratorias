# **Casos de Dengue no Brasil - 2000 a 2019**

- A dengue é uma doença febril causada por vírus, caracterizada principalmente por febre alta de início rápido. Dengue é uma palavra espanhola que significa “manha” ou “melindre”, características que o doente costuma apresentar devido ao mal-estar provocado pelos sintomas. Os sintomas normalmente duram até sete dias.

- Segundo o portal de notícias [Agência Brasil](https://agenciabrasil.ebc.com.br/saude/noticia/2023-12/brasil-e-pais-com-mais-casos-de-dengue-no-mundo-mostra-dados-da-oms), o Brasil lidera o número de casos de dengue no mundo, com **2,9 milhões** de casos registrados somente em 2023, sengundo a Organização Mundial de Saúde (OMS). E o ano de 2024 iniciou com um aumento significativo de casos registrados e de mortes pela doença.

- Com isso, é mais do que necessário termos dados e análises concretas de registros de casos, espalhamento da doença e dos seus fatores de incidência.

## **Objetivo**

Fazer uma Análise Exploratória de Dados utilizando um conjunto de dados sobre casos de dengue no Brasil entre os anos 2000 e 2019.

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
