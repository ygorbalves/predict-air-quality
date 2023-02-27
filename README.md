# Predict Air Quality - São Paulo City

### Capital paulista tem índice de poluição do ar acima do recomendado pela OMS há duas décadas.
![air-polution](https://user-images.githubusercontent.com/77367268/221709584-27d02f89-f7c5-4828-a470-29b9751abca5.png)

Fonte: https://diariodotransporte.com.br/2022/05/26/capital-paulista-tem-poluicao-do-ar-abaixo-do-recomendado-pela-oms-ha-duas-decadas/

Portanto, a partir da API https://aqicn.org/ é possível obter os dados em tempo real da qualidade do ar de diversas cidades no mundo. Além disso, também é possiver obter os dados históricos das cidades. Desse modo, estou implementando um algoritmo para prever a qualidade do ar na cidade de São Paulo. 

O projeto será composto das seguintes etapas:

- Preparação dos dados históricos, tratando missing values, outliers, feature selection. 
- Análise exploratória dos dados para formação de insights sobre o problema abordado. 
- Implementação dos modelos preditivos.
- Seleção dos melhores modelos com processamento em batch (offline).
- Elaboração do pipeline do projeto.
- Coleta de dados em tempo real via a API do aqicn.org, agendada pelo Github Actions.
- Deploy do modelo via Streamlit e re-treino periódico. 

O objetivo primário é realizar o projeto completo em uma espécie de MVP (Minimum Viable Product) e posteriormente ir aperfeiçoando as etapas até tornar um projeto mais robusto. Entre as possíveis futuras implementações, consta-se deploy da base de dados na AWS, estruturação dos Dados no MySQL, operação do modelo na nuvem.


