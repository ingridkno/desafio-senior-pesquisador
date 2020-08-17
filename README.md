# Desafio Senior Pesquisador - Descrição do Problema

A quantidade de spams que a Senior Sistemas recebe diariamente, não para de crescer. Os tipos de spam são diversos: anúncios de produtos / web sites, esquemas para ganhar dinheiro rápido, correntes, pornografia e etc. Dessa forma, aos seus candidatos a pesquisador, a Senior propôs o desafio considerando uma base de mensagens classificada em "Comum" ou "Spam". 

## Descrição da Base de Dados

O arquivo sms_senior.csv contém vários exemplos de mensagens comuns (4827 unidades) e mensagens spams (747 unidades). As mensagens foram submetidas a uma etapa de mineração de
texto, com o objetivo de identificar as palavras mais frequentes na base de dados. 

## Etapas do Desafio

O desafio constitui-se em duas etapas. 

A primeira etapa se deu pela análise de texto das mensagens da base de dados "sms-senior.csv" a partir da estatística descritiva. Foram quantificadas as palavras mais frequentes, as mensagens "spams" e "comuns" ao longo dos meses, os indicadores estatísticos para o número total de palavras mensalmente e os dias por mês com mais mensagens.

A segunda etapa foi a geração de um modelo de classificação para mensagens "spam" e "comum". Para este modelo, foi escolhido o método Multinomial de Naive Bayes.


## Executando o código

Para resolução do Desafio Senior, o código foi desenvolvido num Jupyter Notebook usando da linguagem Python. Os arquivos necessários para sua execução estão na mesma pasta do código sendo que o mesmo foi redigido seguindo a ordem das tarefas do documento "desafio-pesquisador-2020.pdf":

Primeira Etapa
1. Exibir gráfico as palavras mais frequentes em toda a base de dados (Ex.: gráfico de barras,nuvem de palavras, etc).
2. Exibir gráfico com as quantidades de mensagens comuns e spams para cada mês;
3. Calcular o máximo, o mínimo, a média, a mediana, o desvio padrão e a variância da quantidade
total de palavras (Word_Count) para cada mês;
4. Exibir o dia de cada mês que possui a maior sequência de mensagens comuns (não spam).

Segunda Etapa
A segunda etapa consiste em aplicar um método capaz de classificar automaticamente as mensagenscomo “comum” e “spam”. 

## Autora

* **Ingrid Knochenhauer de Souza** 

## Reconhecimento

* Senior Sistemas
