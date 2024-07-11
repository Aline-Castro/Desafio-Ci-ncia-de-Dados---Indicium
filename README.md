# Desafio Cientista de Dados: Análise de Dados de Filmes

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter Notebooks](https://img.shields.io/badge/Jupyter_Notebooks-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org/)
[![Plotly](https://img.shields.io/badge/Plotly-40BFFF?style=for-the-badge&logo=plotly&logoColor=white)](https://plotly.com/)
[![Statsmodels](https://img.shields.io/badge/Statsmodels-757575?style=for-the-badge)](https://www.statsmodels.org/)
[![WordCloud](https://img.shields.io/badge/WordCloud-2C3E50?style=for-the-badge)](https://github.com/amueller/word_cloud)
[![Scikit Learn](https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![Pickle](https://img.shields.io/badge/Pickle-FFD700?style=for-the-badge)](https://docs.python.org/3/library/pickle.html)
[![TextBlob](https://img.shields.io/badge/TextBlob-15AABF?style=for-the-badge)](https://textblob.readthedocs.io/)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)](https://pytorch.org/)
[![Transformers](https://img.shields.io/badge/Transformers-54B689?style=for-the-badge)](https://huggingface.co/transformers/)
[![Regular Expression](https://img.shields.io/badge/Regular_Expression-4D4D4D?style=for-the-badge)](https://docs.python.org/3/library/re.html)
[![Warnings](https://img.shields.io/badge/Warnings-FFA500?style=for-the-badge)](https://docs.python.org/3/library/warnings.html)


## Introdução

Bem-vindo(a) ao Desafio de Cientista de Dados proposto pela INDICIUM, projetado para testar habilidades em resolver problemas de negócios, análise de dados e modelagem preditiva. Este desafio visa avaliar entendimento de conceitos estatísticos em modelos preditivos, criatividade na resolução de problemas e aplicação de modelos básicos de machine learning.

## Desafio

A tarefa é analisar um conjunto de dados de filmes para orientar o desenvolvimento do próximo filme de um estúdio de Hollywood chamado PProductions. Essa análise precisa ser detalhada, considerando diversos fatores devido aos altos investimentos financeiros envolvidos.


## Instalação

Para instalar e executar este projeto, siga as instruções abaixo:

1. Clone o repositório para a sua máquina local usando `git clone`;
2. Navegue até a pasta do projeto usando `cd nome-da-pasta`;
3. Instale as dependências necessárias usando `pip install -r requirements.txt`;
4. Abra o arquivo `LH_CD_ALINECASTRO.ipynb` em um ambiente Jupyter Notebook;
5. Faça o upload da base de dados disponibilizada 'desafio_indicium_imdb.csv';
6. Você pode visualizar no Colab (clicando no badge do Colab no início do projeto).

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

## Bibliotecas Utilizadas

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scipy.stats`
- `plotly`
- `statsmodels`
- `wordcloud`
- `sklearn`
- `pickle`
- `textblob`
- `torch`
- `transformers`
- `re`
- `warnings`

___
### Contribuições

Contribuições para este projeto são bem-vindas. Por favor, abra uma issue ou um pull request para discutir possíveis melhorias ou adições ao projeto.

## Autora:

###### Desenvolvido por Aline Castro. Você pode entrar em contato através do LinkedIn:<br>
[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alinecastrosantos/)
---

