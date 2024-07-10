# Desafio de Cientista de Dados: Análise de Dados de Filmes

## Introdução

Bem-vindo ao Desafio de Cientista de Dados, projetado para testar habilidades em resolver problemas de negócios, análise de dados e modelagem preditiva. Este desafio visa avaliar entendimento de conceitos estatísticos em modelos preditivos, criatividade na resolução de problemas e aplicação de modelos básicos de machine learning.

## Desafio

A tarefa é analisar um conjunto de dados de filmes para orientar o desenvolvimento do próximo filme de um estúdio de Hollywood chamado PProductions. Essa análise precisa ser detalhada, considerando diversos fatores (a incorporação de dados externos é permitida e encorajada) devido aos altos investimentos financeiros envolvidos.

## Entregas

1. Análise Exploratória de Dados (EDA), mostrando as principais relações entre as variáveis e apresentando hipóteses relevantes.

2. Respostas às seguintes perguntas:
   - Qual filme você recomendaria para uma pessoa que você não conhece?
   - Quais são os principais fatores associados com altas expectativas de faturamento de um filme?
   - Quais insights podem ser obtidos a partir da coluna Overview? É possível inferir o gênero do filme a partir desta coluna?
   - Explique como você preveria a nota do IMDb a partir dos dados. Quais variáveis e/ou transformações você usaria e por quê? Que tipo de problema estamos resolvendo (regressão, classificação)? Qual modelo se ajusta melhor aos dados, seus prós, contras e a métrica de desempenho escolhida?

3. Dado um filme com as seguintes características:
   ```
   {'Series_Title': 'The Shawshank Redemption',
    'Released_Year': '1994',
    'Certificate': 'A',
    'Runtime': '142 min',
    'Genre': 'Drama',
    'Overview': 'Dois homens presos criam laços ao longo de vários anos, encontrando consolo e redenção através de atos de decência comum.',
    'Meta_score': 80.0,
    'Director': 'Frank Darabont',
    'Star1': 'Tim Robbins',
    'Star2': 'Morgan Freeman',
    'Star3': 'Bob Gunton',
    'Star4': 'William Sadler',
    'No_of_Votes': 2343110,
    'Gross': '28,341,469'}
   ```
   Qual seria a nota do IMDb?

4. O modelo desenvolvido foi salvo no formato .pkl.

## Dicionário de Dados

O conjunto de dados de treinamento possui 15 colunas:
* Series_Title – Nome do filme
* Released_Year - Ano de lançamento
* Certificate - Classificação etária
* Runtime – Tempo de duração
* Genre - Gênero
* IMDB_Rating - Nota do IMDB
* Overview - Overview do filme
* Meta_score - Média ponderada de todas as críticas 
* Director – Diretor
* Star1 - Ator/atriz #1
* Star2 - Ator/atriz #2
* Star3 - Ator/atriz #3
* Star4 - Ator/atriz #4
* No_of_Votes - Número de votos
* Gross - Faturamento

---

