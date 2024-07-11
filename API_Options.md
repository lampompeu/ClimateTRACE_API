## Filtro de busca

**countries**
Lista de países representados por três letras (alpha3)
ex: "BRA", "ITA", "ARG"

[Mais opções](https://api.climatetrace.org/v4/definitions/countries)

**sectors**
Lista de setores
ex: "agriculture", "mineral-extraction", "forestry-and-land-use", "fossil-fuel-operations"

[Mais opções](https://api.climatetrace.org/v4/definitions/sectors)

**subsectors**
Lista de subsetores
ex: "forest-land-fires", "synthetic-fertilizer-application", "road-transportation"

[Mais opções](https://api.climatetrace.org/v4/definitions/subsectors)

**continents**
Utiliza países de continentes especificados
ex: "South America", "Asia"

[Mais opções](https://api.climatetrace.org/v4/definitions/continents)

**groups**
Utiliza grupos específicos de países 
ex: "g20", "eu", "arab_league", "coalition_for_rainforest_nations"

[Mais opções](https://api.climatetrace.org/v4/definitions/groups)

**gas**
Filtrar emissão por gases. Para a função *summary*. Apenas um gás pode ser solicitado por vez.
Possíveis valores (str):
- n2o
- co2
- ch4
- co2e_20yr
- co2e_100yr

## Outras opções

**file_path** 
Caso for incluído, faz o download para o caminho/arquivo especificado. 

**ownership**
Caso ``TRUE``, inclui dados de controladores das fontes de emissão.   
