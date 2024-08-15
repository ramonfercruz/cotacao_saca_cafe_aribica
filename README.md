# Café e tecnologia: Seleção de métodos para projeção do preço da saca de café


Projeto consiste no codigo utlizado para elaboração do trabalho apresentado para obtenção do título de especialista em Data
Science e Analytics – 2023

- Graficos: Graficos criado para confecção do trabalho
- Modelos criados para elaboração do trablaho
- Café e tecnologia: Seleção de métodos para projeção do preço da saca de café.pdf:  documento final


## Resumo

  O Brasil é o principal produtor de café no mundo, e a sua cadeia produtiva gera forte
impacto na economia nacional, porém o produto tem sofrido grandes variações de preço nos
últimos anos, o que nem sempre é benéfico para o produtor rural. Estas variações geram
incertezas no mercado cafeicultor. Com base neste cenário, foi realizado um estudo de três
variáveis: dólar, inflação e preço do diesel, comprovando o impacto destes fatores no preço
do café, por meio de correlação e teste de causalidade. Por fim, foi efetuada a criação de
modelos que possibilitem a previsão de valores futuros utilizando as variáveis exógenas
analisadas com o objetivo de criar ferramentas que auxiliem a tomada de decisão por parte
dos agentes atuantes no mercado produtor de café. Foi testado a utilização de redes neurais
em comparação a abordagem de estatísticas tradicionais, o ARIMA e modelos de aprendizado
de máquina, random forest e xgboost. Por meio da validação cruzada foi possível concluir que
as redes neuras apresentaram bons resultados, porém o modelo ARIMA se mostrou mais
estável e constante entregando os melhores resultados.
Palavras-chave: Series Temporais; ARIMA; Validação Cruzada; Aprendizado de Máquina,
redes neurais.

## Considerações Finais 

Neste trabalho foi possível analisar a série temporal da cotação mensal da saca de
café, descrever o seu comportamento, avaliar fatores que influenciam o preço alvo e propor
métodos de natureza supervisionada para estimação de valores futuros da série temporal. Os
modelos propostos foram avaliados utilizando o método de validação cruzada e as variáveis
exógenas estudas foram o dólar, IPCA 12M e o preço médio do diesel.
Com base nos dados coletados, análises gráficas, cálculo das correlações e teste de
Granger efetuado, é possível concluir que as variáveis exógenas coletas possuem forte
influência na cotação da saca de café dentro do período analisado. Porém esses três fatores
ainda não são suficientes para explicar toda a variação do preço da saca de café.
Após as análises efetuadas, foi possível realizar a implementação de diferentes
modelos e algoritmos de aprendizado de máquina, redes neurais e estatística clássica. Dentre 
essas implementações foi possível concluir que o método tradicional conhecido como
abordagem de Box e Jenkins, o ARIMA, apresentou o melhor resultado demonstrando
métricas de erros constantes, mesmo em momentos de grande quebra estrutural e oscilações
na cotação da saca de café.
Em pesquisas futuras proponho a investigação de variáveis ditas como relevantes,
porém que não estavam disponíveis para estudo dentro do período de realização deste
trabalho, informações como: os preços de insumos agrícolas, dados do clima nas áreas
produtoras de café (temperatura, volume de chuvas, geada, etc.), taxa Selic, oferta de grãos
por parte do mercado cafeicultor e demandas por grãos por parte dos consumidores. Quanto
as implementações de modelos ainda existem espaço para aprofundar na otimização dos
parâmetros ou na abordagem de outras técnicas.


## Referências


Breiman, Leo. 2001, Random Forests. Disponível em
<https://link.springer.com/article/10.1023/a:1010933404324>. Acesso em: 08/07/2023
Centro de Estudos Avançados em economia Aplicada [CEPEA]. 2020. Agronegócio e a
Inflação. Disponível em:
<https://www.cepea.esalq.usp.br/upload/kceditor/files/Cepea_agro_e_inflacao_(2).pdf>.
Acesso em 02 de junho de 2023.


Bergmeira, Christoph. Hyndman, Job J. Bonsoo, Koob. 2017. A Note on the Validity of
Cross-Validation for Evaluating Autoregressive Time Series Prediction. Acesso em:
<https://perma.cc/YS3J-6DMD>. Acesso em 10 setembro 2023


Faceli, Katti. Lorena, Ana C. Gama, João. et al. 2021. Inteligência Artificial: Uma Abordagem
de Aprendizado de Máquina. Grupo GEN. Rio de Janeiro, RJ, Brasil. Disponível em:
https://integrada.minhabiblioteca.com.br/#/books/9788521637509/. Acesso em: 24 mar.
2023.


Gèron, Aurélio. 2021. Mãos à Obra: Aprendizado de Máquina com Scikit-Learn, Keras &
TensorFlow: Conceitos Ferramentas e Técnicas para construção de sistemas inteligentes.
2ed. Alta Books. Rio de janeiro, RJ, Brasil.


Harrison, Matt. 2020. Machine Learning: Guia de Referência Rápida. 1ed. Novatec Editora
Ltda. São Paulo, SP, Brasil.


Haykin, Simon. 2001. Redes neurais princípios e prática. Londrina, Bookman Companhia
Editora. Porto Alegre, RS, Brasil. Disponível em:
<https://integrada.minhabiblioteca.com.br/#/books/9788577800865/>. Acesso em: 12 mar.
2023.


Morettin, Pedro A. Toloi, Clélia M. C. 2018. Análise de Séries Temporais: Modelos lineares
univariados. Volume 1. Editora Blucher. São Paulo, SP, Brasil. Disponível em:
<https://integrada.minhabiblioteca.com.br/#/books/9788521213529/>. Acesso em: 12 março
de 2023.


Morettin, Pedro A. Toloi, Clélia M. C. 2020. Análise de séries temporais: Modelos
multivariados e não lineares. Volume 2. Editora Blucher. São Paulo, SP, Brasil. Disponível
em: <https://integrada.minhabiblioteca.com.br/#/books/9786555060065/>. Acesso em: 20
setembro de 2023.


Morettin, Pedro A. 2017. Econometria Financeira: Um Curso em Séries Temporais
Financeiras. Editora Blucher. São Paulo, SP, Brasil. Disponível em:
<https://integrada.minhabiblioteca.com.br/#/books/9788521211310/>. Acesso em: 22 março
de 2023.


Neves, Cesar das. Rossi, José W. 2014. Econometria e Séries Temporais com Aplicações à
Dados da Economia Brasileira. Grupo GEN. São Paulo, SP, Brasil. Disponível em:
<https://integrada.minhabiblioteca.com.br/#/books/978-85-216-2685-5/>. Acesso em: 12
março de 2023.


Nielsen, Ailen. 2021. Análise Prática de Séries Temporais: Predição com Estatística e
Aprendizado de Máquina Starlin. 1ed. Alta Editora e Consultoria. Rio de Janeiro, RJ, Brasil.


Nogueira, José Guilherme A. NEVES, Marcos F. 2015. Estratégias para a Cafeicultura no
Brasil. Editora Atlas. São Paulo, SP, Brasil. Disponível em:
<https://integrada.minhabiblioteca.com.br/#/books/9788522497867/>. Acesso em: 19 mar.
2023.


Sesso, Patrícia Pompermayer. Filho, Umberto Antonio Sesso; PEREIRA, Luiz Filipe
Protasio. 2021. Dimensionamento do agronegócio do café no Brasil. Disponível em:
<https://ainfo.cnptia.embrapa.br/digital/bitstream/item/225200/1/dimensionamento-doagronegocio-do-cafe-2021.pdf>. Acesso em: 18 maio 2023.
