
##  Music Recommendation System

Projeto desenvolvido em **Python** para criar um sistema de recomendação de músicas baseado em similaridade de atributos sonoros.

###  Funcionalidades

* **Busca inteligente**: permite procurar músicas sem diferenciação entre maiúsculas e minúsculas (*case insensitive*).
* **Recomendação automática**: sugere faixas semelhantes com base em métricas como `danceability`, `energy`, `valence`, `acousticness`, entre outras.
* **Filtragem por humor**: classificação simples entre músicas “animadas” e “calmas”.
* **Visualização de dados**: uso de **matplotlib** e **plotly** para comparar faixas e gerar gráficos interativos.

###  Tecnologias utilizadas

* **Python 3**
* **Pandas** (tratamento de dados)
* **NumPy** (operações matemáticas)
* **Plotly / Matplotlib** (visualizações)

###  Lógica geral

1. Carregamento do dataset com informações das músicas.
2. Normalização dos nomes das faixas para permitir buscas flexíveis.
3. Cálculo de similaridade entre músicas a partir dos atributos numéricos.
4. Retorno das recomendações e geração de comparativos visuais.

