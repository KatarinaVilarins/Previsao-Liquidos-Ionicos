# Previsao-Liquidos-Ionicos
O projeto é focado na elaboração de um programa voltado para, com o uso de 4 atributos, previsão de 1 target relacionado a caracterização de líquidos iônicos.



# <h1 align="center"> Previsão Características dos Líquidos Iônicos </h1>
  Esse projeto é voltado para o uso de um dataset referente a Líquidos Iônicos, que em conjunto com um modelo preditivo proposto pelo grupo, possibilita o cálculo de um aspecto desse tipo de material a partir da observação de um padrão existente. Além disso, tem o intuito de documentar os processos de desenvolvimento de códigos e uso de ferramentas que possibilitem um bom desempenho do programa elaborado com conceitos da área de aprendizado de máquina (machine learning).
 
## 🛣 Guia ao leitor 

  O Github serve como repositório do projeto desenvolvido, é possível compreender o trabalho de maneira superficial apenas lendo o Readme em que se encontra, contudo informações adicionais estão disponíveis nos demais arquivos localizados nesse Git.
  
  Para aqueles que possuem interesse em compreender mais aprofundadamente o projeto, há disponível o relatório do projeto desenvolvido. O documento possui um resumo, uma introdução, a discussão acerca do desenvolvimento do trabalho além de exploração de termos mais técnicos contendo vantagens e desvantagens de optar pelo modelo de regressão selecionado pelo grupo. Há também nele a metodologia e a coclusão acerca dos resultados obtidos na aplicação do algoritmo desenvolvido.

  Outra opção é visualizar o código em operação que está disponibilizado em formato de notebook em python. Nele estão contidos os códigos e breves cometários para esclarecer o papel desempenhado pelas ferramentas utilizadas e os resultados obtidos, além de discussões acerca deles e dos gráficos visualizados.

  O objetido maior dos documentos é uma autossustentação, de maneira a possibilitar uma melhor compreensão do trabalho por si só!

## 📖 Motivação do Projeto...
   Após um momento inicial de discussão, o grupo buscou conciliar as áreas de interesse de todos os integrantes. O objetivo era escolher uma temática que fosse relevante para a indústria e, ao mesmo tempo, não prejudicial ao meio ambiente. Além disso, procurávamos um objeto de estudo que se destacasse aos olhos do grupo. Ao explorar temas que contemplassem esses aspectos e que apresentassem vantagens para um aprofundamento, nos deparamos com a opção de investigar os Líquidos Iônicos. Essa escolha foi motivada pela interdisciplinaridade, suas propriedades únicas, os avanços em pesquisa, as diversas aplicações industriais e seu potencial sustentável.
  
  Uma busca constante do meio de produção indústrial é por solventes mais adequados a ao processo de produção, isto é, solventes mais biodegradáveis, mais estáveis e até mais baratos. Os líquidos iônicos apresentam tanto grande estabilidade térmica e baixa viscosidade quanto uma menor volatilidade e maior capacidade de biodegradação, essa são propriedades de demasiado interesse ao se discutir um bom solvente.
  
  Portando, diante dos diversos fatores que embasavam um bom campo de investimento em pesquisa optamos por explorá-lo colocando em prática alguns dos aprendizados na área de aprendizado de máquina, visando a elaboração de uma ferramenta de predição de propriedades de líquidos iônicos a partir da visualização de outras. 


### Objetivo e formulação da pergunta/ hipótese do projeto
  Com a aplicação do modelo de predição optado pelo grupo, no caso foi a Floresta Aleatória, o objetivo é prever a propriedade de interção da fase processada com o soluto por meio de interações de dispersão (interaction of the process phase with solute through dispersion interactions) a partir dos demais atributos disponíveis do dataset. Essa informação tornará possível elaborar a hipótese de qual seria um material mais ou menos adequado para ser utilizado em aplicações como extração de compostos orgânicos de misturas ou na dissolução de catalisadores em reações químicas. Em conjunto com essa iniciativa, há também o interesse em prever essa propriedade pois ela possui grande dificuldade no processo de medição. De acordo com o Readme associado ao banco de dados utilizados como referência a letra correspondente a propriedade de interesse é 'E', então o grupo fará uso das demais para calcular de maneira mais precisa possível o valor dela.
### 🧰 Funcionamento

Para um maior detalhamento do funcionamento do código é possível tanto acessar o notebook disponível quanto o relatório também presente.

 `Seleção dos atributos e targets`: Primeiro basta escolher quais são as informções que serão utilizadas para prever o target 

 `Explorar o formato dos dados presente`: É necessário, então, que os dados sejam analisados para avaliar se é necessário ou não a etapa de normalização. Essa etapa é importante também para verificar se o modelo escolhido é adequado para o padrão de dados que estão sendo utilizados

 `Teste e treino`: Foi feito então a separação dos dados em conjuntos chamados de teste e treino para utilizar então em etapas futuras para a elaboração do código em sua totalidade
 
 `Otimização de hiperparâmetros`: É indispensável para um bom desempenho do modelo que sejam feitos algumas tentativas de ajuste/otimização dos hiperparâmetros

 `Botar em prática`: Então basta só treinar o modelo com os melhores parâmetros e fazer a previsão.

 `Análise do resultado`: Apesar de as etapas anteriores fornecerem um valor para o target selecionado é necessário calcular a relação do que foi previsto com o que de fato é real para conseguir entender o quão bom o desempenho do modelo elaborado é.


 ## ☑️ O que usamos no trabalho?
 
Para que fosse possível analisar os dados referentes ao material de interesse do grupo foram necessários alguns fatores:

`Um dataset sobre Líquidos Iônicos`: que no caso o utilizado foi um fornecido pelo professor Leandro das Merces Silva (link: https://digital.library.unt.edu/ark:/67531/metadc307526/)

`Um caderno de programação`:  o adotado foi o python em sua versão 3.11.6;

`Bibliotecas`: Pandas - para tratamento de dados, Skicit-Learn; matplotlib e seaborn- para plotagem de gráficos; 

`Literatura sobre o tema` : Fizemos a leitura de artigos e trabalhos publicados acerca dos materiais iônicos sobre como são utilizados, sintetizados e como se comportam diante de diferentes situações. (Todos estão documentados na área de referências).

`Referências`: 

Banco de dados sobre Líquidos Iônnicos: (link: https://digital.library.unt.edu/ark:/67531/metadc307526/)​

SCIKIT-LEARN. scikit-learn: machine learning in Python. Disponível em: <https://scikit-learn.org/stable/>. ​

.Líquidos Iônicos - Alguns aspectos sobre as propriedades, preparação e aplicações. Disponível em: <https://wp.ufpel.edu.br/wwverde/files/2014/12/L%C3%ADquidos-I%C3%B4nicos.pdf​>. Acesso em: 2 set.2024

Halper, Marin S; Ellenbogen, James C. Supercapacitors: A brief overview. Disponível em: <https://www.mitre.org/sites/default/files/pdf/06_0667.pdf>

Liu, Huan; Yu, Haijun. Ionic liquids for eletrochemical energy storage devices aplication. Disponível em: <https://www.sciencedirect.com/science/article/abs/pii/S1005030218302640>
 


Por meio do funcionameto em conunto dessas ferramentas é possível garantir o retorno da informação target do material recebendo quatro atributos referentes a ele.

### ✒️ Autores

| <img loading="lazy" src="https://avatars.githubusercontent.com/marcotlr" width=115><br> <sub>Marco Tulio<br> [Github](https://github.com/marcotlr) </sub>|  <img loading="lazy" src="https://avatars.githubusercontent.com/KatarinaVilarins" width=115><br><sub>Katarina Vilarins<br> [GitHub](https://github.com/KatarinaVilarins) </sub> |  <img loading="lazy" src="https://avatars.githubusercontent.com/PedroBramante" width=115><br><sub>Pedro Bramante<br> [Github](https://github.com/PedroBramante) </sub> | |
| :---: | :---: | :---: | :---: |
