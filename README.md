# IMDB - Exercício de Regressão Linear

Este repositório contém um exercício de regressão linear aplicado ao dataset do IMDB, que inclui notas de filmes e diversas outras variáveis relacionadas. O objetivo é comparar diferentes abordagens para avaliar qual estratégia resulta em um modelo de melhor desempenho.

## Objetivo

Nosso objetivo é comparar diferentes abordagens para avaliar qual estratégia resulta em um modelo melhor. Para isso criamos dois modelos:

- Modelo 1 com os valores NaN removidos.
- Modelo 2 com os valores NaN sendo convertidos em valores nulos.

Para esse exercício utilizamos o dataset IMDB de filmes (disponível no repositório) e criamos os modelos para prever **IMDB_RATING** utilizando dados numéricos disponibilizados no próprio arquivo de dados.

## Conteúdo

Preprocessamento de Dados: Tratamento dos dados, "dummyzando" todos os valores categóricos julgados como úteis e retirando os valores que não serão usados.

Construção de Modelos: Desenvolvimento de modelos de regressão linear para diferentes versões do dataset (com e sem valores ausentes).

Avaliação de Desempenho: Comparação dos modelos através de métricas como o R², visando determinar qual abordagem proporciona previsões mais precisas sobre as notas dos filmes.

Conclusões: Análise dos resultados obtidos e recomendações sobre a melhor prática para lidar com valores ausentes em datasets similares.

## Conclusões Principais

Modelo sem valores NaN: Demonstrou um desempenho superior, com uma diferença de apenas 1.83% entre os scores de treinamento e teste.
    
Modelo com valores NaN: Foi menos eficaz, apresentando uma diferença de 4.51% entre os scores de treinamento e teste.

## Para quem é esse pequeno projeto?

Este projeto é ideal para quem deseja explorar a aplicação de regressão linear em dados reais, como as notas de filmes do IMDB, e entender o impacto de diferentes técnicas de tratamento de dados ausentes na precisão dos modelos preditivos.

Se sinta confortável para usar esse projeto como referência.
