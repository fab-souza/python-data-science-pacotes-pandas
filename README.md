# python-data-science-pacotes-pandas

![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=Finalizado&color=GREEN&style=for-the-badge)

![Badge code size](https://img.shields.io/github/languages/code-size/fab-souza/python-data-science-pacotes-pandas)
![Badge de Atualização](https://img.shields.io/github/last-commit/fab-souza/python-data-science-pacotes-pandas)

| :placard: Vitrine.Dev |    |
| -------------  | --- |
| :sparkles: Nome        | **Python para Data Science: Funções, Pacotes e Pandas**
| :label: Tecnologias | python
| :rocket: URL         | https://github.com/fab-souza/python-data-science-pacotes-pandas/
| :fire: Desafio     | [Python para Data Science: linguagem e Numpy](https://www.alura.com.br/curso-online-python-funcoes-pacotes-pandas)

![](https://user-images.githubusercontent.com/67301805/205658883-f1b3309f-43b7-46bd-841d-b02673002503.jpg#vitrinedev)

Neste curso, aprendi sobre as tuplas e dicionários, de como criá-las, executar seleções e iterações. E depois, sobre os principais comandos do Pandas. Por exemplo, abrir um arquivo ‘.csv’, ver os tipos de cada variável e de como visualizar um intervalo de linhas do dataframe. Depois aprendi sobre o ‘.loc’, ‘.iloc’, ‘.isna’, ‘fillna’ e ‘.dropna’.

Usei a base de dados, oferecida pelo Colab, para treinar. Primeiro, fiz a leitura do arquivo csv, depois verifiquei os tipos de variáveis presentes no dataframe. Escolhi duas variáveis para gerar estatísticas descritivas, ‘housing_median_age’ e ‘median_house_value’, com o ‘.describe()’, porque eu não queria ver a estatística de todas as variáveis. Para ter uma visão geral do dataframe, usei o ‘.info()’. Estou fazendo este treino no dia 07/12/22, por isso selecionei o intervalo de linhas [7, 12]. Em seguida, utilizei o ‘.loc’ para ver todas as informações do índice 7 do dataframe, também fiz uma seleção dos índices 7 e 12, primeiramente visualizando todas as informações, depois restringi a visualização a duas variáveis, ‘housing_median_age’ e ‘median_house_value’. Para o ‘.iloc’, continuei a seleção de [7:12], porém também apresentei o dataframe de uma forma diferente, mostrando as variáveis [0, 1, -1, 5], ‘longitude’, ‘latitude’, ‘median_house_value’ e ‘population’, respectivamente. Também criei uma variável para receber todas linhas que tinham um ‘housing_median_age’ menor do que 5, depois selecionei as linhas que também tinham um ‘median_income’ maior do que 10. Por fim, usei o ‘.query()’ para repetir a última seleção.
