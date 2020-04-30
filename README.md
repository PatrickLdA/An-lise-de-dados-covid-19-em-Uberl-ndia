# Análise de dados covid-19 em Uberlândia
Captura de dados e análise das métricas a respeito do avanço do Coronavirus na cidade de Uberlândia.


## Introdução
Este projeto foi feito para analisar as principais métricas do covid-19 na cidade de Uberlândia, MG. As bases **dataset coronavirus uberlandia** e **acoes** são usadas durante a análise (e são atualizadas periodicamente por mim).

Este também é um trabalho de aperfeicoamento das minhas habilidades em Python e análise de dados, além de uma contribuição para a nossa cidade. Qualquer dúvida, sugestão e crítica serão bem vindas em [patrickluizdearaujo@gmail.com](patrickluizdearaujo@gmail.com).


## Bases de dados
A primeira base é **dataset coronavirus uberlandia.csv** com as principais métricas da cidade. Esta base contém os seguintes campos:
- Data: data do boletim
- Casos suspeitos: quantidade de casos que aguardam teste e são suspeitos para o COVID-19. Valor cumulativo
- Casos confirmados: casos que foram testados e apresentaram resultado positivo para COVID-19. Valor cumulativo
- Internações UTI:número de internações na UTI
- Internações enfermaria: número de internações na enfermaria
- Altas UTI (24h): altas de internados na UTI nas últimas 24h
- Altas enfermaria (24h): altas de internados na enfermaria nas últimas 24h
- Óbitos suspeitos: óbitos em investigação por suspeita de coronavirus
- Óbitos confirmados: testes em óbitos suspeitos com resultado positivo
- Óbitos negativos: testes em óbitos suspeitos com resultado negativo
- Internações totais: número total de internações
- Internações sala de emergência: internações em salas de emergência
- Altas acumuladas UTI (desde 14/04/2020): altas de internados em UTI desde o dia 14/04
- Altas acumuladas enfermaria (desde 14/04/2020): altas de internados em enfermaria desde o dia 14/04
- Índice de ocupação UTI: porcentagem dos leitos de UTI disponíveis na cidade que estão ocupados


A segunda base é **acoes.csv** que contém:
- Data: data do ocorrido
- Info: resumo do acontecimento


Tentarei manter tudo atualizado em relação ao dia anterior.


## Código
O código inteiro das análises está em um notebook python único, chamado **python code.ipynb** devidamente comentado.


## Extras
Os arquivos * *dataset coronavirus uberlandia.ods* * e * *acoes.ods* * são usados por mim para revisão e inserção de novos dados. O arquivo * *timeline.png* * é usado para melhor visualização das notícias, visto que é uma imagem muito grande e pode ficar dificil de enxergar no código.


## Contato
Gostou do meu trabalho? Tem sugestões, críticas ou conselhos? Você pode me achar aqui:
- Email: [patrickluizdearaujo@gmail.com](patrickluizdearaujo@gmail.com)
- [LinkedIn](https://www.linkedin.com/in/patrick-luiz-de-ara%C3%BAjo-b91565131/)
