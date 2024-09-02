# Desafio de Data Engineering - Júnior

## Objetivo

O objetivo deste desafio é coletar dados de uma API de jogos (MMO), processá-los e responder a algumas perguntas sobre esses dados. Você deve utilizar bibliotecas como **Pandas** e **PySpark** para a manipulação e análise dos dados, e gerar gráficos para ilustrar suas respostas com qualquer biblioteca do Python.

## Tempo

1 semana para o envio

## API

Você irá coletar os dados da seguinte API: [API de Jogos](https://www.mmobomb.com/api1/games).

A API retorna uma lista de jogos com várias informações, como título, gênero, plataforma, desenvolvedor, data de lançamento, entre outras.
Aqui está a documentação da API [MMO](https://www.mmobomb.com/api)

## Tarefas

1. **Coleta de Dados:**
   - Utilize a API fornecida para coletar os dados de jogos. (Utilize Python Requests)
   - Armazene os dados em um DataFrame utilizando a biblioteca **Pandas**.

2. **Transformação de Dados:**
   - Filtre os jogos lançados após o ano de 2008. (Utilizando PySpark)
   - Crie uma nova coluna que indique a antiguidade do jogo com base no ano de lançamento (Ex: `Novo`, `Antigo`).

3. **Análise de Dados:**
   - Qual o gênero de jogo mais comum na lista?
   - Quantos jogos foram desenvolvidos por "NCSOFT"?
   - Qual é o jogo mais antigo da lista?
   - Quantos jogos estão disponíveis para a plataforma "Web Browser"?

4. **Visualização de Dados:**
   - Crie um gráfico de barras mostrando a quantidade de jogos por gênero.
   - Crie um gráfico de linhas mostrando o número de jogos lançados por ano.
   - Crie um gráfico de pizza para visualizar a proporção de jogos por plataforma.

5. **Processamento com PySpark:**
   - Carregue os dados em um DataFrame do PySpark.
   - Realize as mesmas transformações e análises feitas com Pandas utilizando PySpark.

6. **Documentação e Entrega:**
   - Documente todo o processo de coleta, transformação, análise e visualização dos dados.
   - Organize o código e os gráficos gerados em um Jupyter Notebook ou um script Python bem estruturado.
   - Faça o upload do seu código e das visualizações em um repositório no GitHub.

## Requisitos Técnicos

- Utilizar **Python** (3.7+)
- Bibliotecas: **Pandas**, **PySpark**, **Matplotlib** ou **Seaborn**
- Fazer um Repositório no GitHub com README detalhado sobre como executar o projeto

## Avaliação

Os seguintes critérios serão considerados na avaliação do desafio:

- **Corretude:** As respostas fornecidas estão corretas e bem fundamentadas.
- **Clareza:** O código está bem organizado e documentado.
- **Eficiência:** O código foi otimizado para desempenho quando necessário.
- **Visualização:** Os gráficos são claros e informativos.

## Dicas

- Leia a documentação da API para entender melhor os dados disponíveis. [MMO](https://www.mmobomb.com/api)
- Utilize notebooks como Jupyter para organizar o processo de análise.
- Teste diferentes tipos de gráficos para encontrar a melhor forma de representar os dados.
- Tenha criatividade

Boa sorte e bom trabalho!
