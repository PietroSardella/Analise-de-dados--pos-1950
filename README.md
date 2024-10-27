Análise de Dados sobre Artistas Contemporâneos
# Introdução
Este projeto visa explorar e analisar os dados de artistas contemporâneos utilizando o conjunto de dados disponível do Tate, que contém informações sobre artistas e suas obras. O foco da análise é entender a distribuição de gêneros, a idade dos artistas e as nacionalidades dos mesmos, especialmente aqueles nascidos após 1950.

# Objetivos do Projeto
Visualizar a Distribuição de Gêneros: Analisar a proporção de artistas masculinos e femininos e sua evolução ao longo do tempo.
Analisar a Idade dos Artistas: Calcular a idade dos artistas contemporâneos e visualizar sua distribuição.
Explorar Nacionalidade: Identificar os países de origem mais comuns entre os artistas e analisar como o gênero está distribuído entre esses países.
Criar Gráficos Informativos: Utilizar gráficos para apresentar visualmente os dados e insights obtidos durante a análise.
# Dados Utilizados
Os dados utilizados neste projeto são:

artist_data.csv: Contém informações sobre os artistas, incluindo nome, gênero, ano de nascimento e lugar de nascimento.
artwork_data.csv: Contém informações sobre as obras de arte, incluindo título, ano de criação, técnica utilizada e informações sobre a aquisição.
Estrutura dos Dados
artist_data.csv:

id: Identificador único do artista
yearOfBirth: Ano de nascimento do artista
gender: Gênero do artista
placeOfBirth: País de nascimento do artista
artwork_data.csv:

id: Identificador único da obra
artist: Nome do artista
title: Título da obra
year: Ano em que a obra foi criada
medium: Técnica utilizada na obra
Metodologia
A análise será realizada em várias etapas, incluindo a leitura dos dados, limpeza e transformação dos dados, visualização dos dados e interpretação dos resultados. Utilizaremos bibliotecas como pandas, seaborn e matplotlib para facilitar a manipulação e visualização dos dados.

Vamos começar!
