
# Projeto: Beyoncé x Ludmilla

Este é um projeto de finalização de curso de Python, desenvolvido em grupo, que explora o impacto das artistas Ludmilla e Beyoncé no cenário musical mundial. O objetivo é entender como cada uma se destaca em popularidade, colaborações e gêneros predominantes, além de analisar sua recepção em diferentes países, com foco na representatividade negra na música.

## Equipe

Este projeto foi realizado pelo grupo:
- Vitória Mota
- Letícia Souza
- Nicoli Silva
- Josane Silva
- Sandy Rodrigues
- Ingrid Almeida

## Objetivo
O objetivo principal é comparar o desempenho de Beyoncé e Ludmilla no Spotify e analisar a influência de ambas na promoção da representatividade negra no setor musical.

## Fontes de Dados
As informações foram coletadas diretamente da **API do Spotify**, incluindo detalhes sobre:
- Popularidade e evolução ao longo dos anos
- Colaborações realizadas por cada artista
- Predominância de gêneros musicais

### Aquisição e Tratamento de Dados
- **Aquisição de Dados**: Utilizou-se a API do Spotify para coletar dados sobre músicas, álbuns, popularidade e colaborações de Beyoncé e Ludmilla.
- **Tratamento de Dados**: Não foi necessária uma etapa extensa de limpeza, pois os dados foram extraídos já em um formato pronto para análise.

## Ferramentas Utilizadas
O projeto foi desenvolvido em **Python** com o auxílio das seguintes bibliotecas:
- **Pandas**: Para manipulação de dados
- **Seaborn**: Para visualização dos dados
- **Spotipy**: Para acessar e consumir a API do Spotify

## Análise de Dados

### 1. Impacto Positivo nas Colaborações
As colaborações musicais apresentam uma popularidade média maior do que as faixas solo tanto para Ludmilla quanto para Beyoncé, indicando que colaborações geram mais impacto e engajamento entre os ouvintes do Spotify.
- **Ludmilla**: A popularidade média de suas colaborações é de 66.9, enquanto a das faixas solo é de 64.0, sugerindo que sua base de fãs reage de maneira relativamente consistente a ambos os tipos de lançamento.
- **Beyoncé**: Com uma diferença maior, suas colaborações têm uma média de 72.5 em popularidade, enquanto suas faixas solo estão em 68.5. Colaborações com artistas renomados, como Jay-Z, tendem a elevar ainda mais sua popularidade.

### 2. Resumo Geral
| Ano | Beyoncé | Ludmilla |
|-----|---------|----------|
| 2019 | Nenhum lançamento relevante (popularidade = 0) | Popularidade inicial de 27 |
| 2021 | Destaque, popularidade de 51 | Cresceu para 40 |
| 2022 | Pico de popularidade (68) | Manteve-se estável com 40 |
| 2023 | Queda para 36 | Sem lançamentos populares |
| 2024 | Recuperação para 58 | Retorno com 55, quase igualando Beyoncé |

Beyoncé apresentou uma trajetória mais volátil ao longo dos anos, com picos e quedas significativas, enquanto Ludmilla teve um crescimento mais estável. O ano de 2024 foi um ponto de convergência, com as duas artistas quase empatadas em popularidade, mostrando que ambas continuam sendo forças relevantes na música.

### 3. Comparação de Seguidores
- **Ludmilla**: 7,7 milhões de seguidores, um número expressivo no cenário brasileiro.
- **Beyoncé**: 38,8 milhões de seguidores, cerca de cinco vezes mais que Ludmilla.

A diferença substancial reflete a presença global e carreira extensa de Beyoncé, enquanto Ludmilla destaca seu impacto crescente, principalmente em países de língua portuguesa.

### 4. Distribuição e Correlação de Streams
- **Distribuição de Streams**: Ambas as artistas têm a maioria das músicas entre 2 a 4 minutos de duração, com uma concentração de streams entre 60 e 70.
- **Correlação**: A correlação entre duração e número de streams é fraca (0.076), sugerindo que a duração das músicas não afeta significativamente o número de streams no período analisado.

### 5. Análise de Playlists
- **Número de Playlists**: Ludmilla está em 10 playlists e Beyoncé em 9. Ludmilla aparece em playlists com mais músicas em média (77 vs 68).
- **Duração das Playlists**: Apesar de estar em playlists mais longas, a duração total das playlists de Beyoncé é maior, com músicas geralmente mais longas.

---

## Como Contribuir
1. Clone o repositório:
   ```bash
   git clone https://github.com/Vigmt/projeto_beyonce-x-ludmilla.git
