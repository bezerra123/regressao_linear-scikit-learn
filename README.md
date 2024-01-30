# regressao_linear-scikit-learn
O projeto de regressão linear foi conduzido com o objetivo de entender e modelar a relação entre variáveis específicas em um conjunto de dados. A técnica de regressão linear foi escolhida por ser adequada quando se suspeita que existe uma relação linear entre as variáveis envolvidas.

projeto 1: consumo de cerveja 
 A cerveja é uma das bebidas mais democráticas e consumidas no mundo. Não sem razão, é perfeito para quase todas as situações, desde o happy hour até grandes festas de casamento.

O objetivo deste treinamento será estimar um modelo de Machine Learning utilizando a técnica de Regressão Linear para demonstrar os impactos das variáveis disponibilizadas neste dataset sobre o consumo de cerveja (Y). No final do projeto teremos um modelo de previsão para o consumo médio de cerveja segundo os inputs de um conjunto de variáveis (X's).

Os dados (amostra) foram coletados em São Paulo - Brasil, em uma área universitária, onde existem algumas festas com grupos de alunos de 18 a 28 anos de idade (média).

Dados:
data - Data
temp_media - Temperatura Média (°C)
temp_min - Temperatura Mínima (°C)
temp_max - Temperatura Máxima (°C)
chuva - Precipitação (mm)
fds - Final de Semana (1 = Sim; 0 = Não)
consumo - Consumo de Cerveja (litros)


Projeto 2: preços de imóveis
 Nosso objetivo neste exercício é criar um modelo de machine learning, utilizando a técnica de Regressão Linear, que faça previsões sobre os preços de imóveis a partir de um conjunto de características conhecidas dos imóveis.

Vamos utilizar um dataset disponível no Kaggle que foi gerado por computador para treinamento de machine learning para iniciantes. Este dataset foi modificado para facilitar o nosso objetivo, que é fixar o conhecimento adquirido no treinamento de Regressão Linear.


Dados:
precos - Preços do imóveis
area - Área do imóvel
garagem - Número de vagas de garagem
banheiros - Número de banheiros
lareira - Número de lareiras
marmore - Se o imóvel possui acabamento em mármore branco (1) ou não (0)
andares - Se o imóvel possui mais de um andar (1) ou não (0)

Etapa 1: Definição do Problema:
O primeiro passo envolveu a definição clara do problema a ser abordado. Isso incluiu a identificação da variável dependente (a ser prevista) e das variáveis independentes (explicativas) que se acredita influenciarem a variável dependente.

Etapa 2: Coleta e Exploração dos Dados:
Os dados necessários para o projeto foram coletados e explorados. Isso incluiu a verificação da qualidade dos dados, lidando com valores ausentes, explorando estatísticas descritivas e visualizações para entender a distribuição e relações preliminares entre as variáveis.

Etapa 3: Pré-processamento dos Dados:
Os dados foram pré-processados para garantir que estivessem em um formato adequado para a modelagem. Isso envolveu a normalização de variáveis, tratamento de outliers e a codificação de variáveis categóricas, se necessário.

Etapa 4: Divisão dos Dados:
Os dados foram divididos em conjuntos de treinamento e teste usando a função train_test_split do scikit-learn. Isso permitiu avaliar o desempenho do modelo em dados não vistos.

Etapa 5: Treinamento do Modelo:
Utilizando a classe LinearRegression do scikit-learn, o modelo de regressão linear foi treinado com os dados de treinamento. Isso envolveu ajustar a linha de melhor ajuste aos dados para minimizar a soma dos quadrados dos resíduos.

Etapa 6: Avaliação do Modelo:
O desempenho do modelo foi avaliado usando métricas apropriadas para regressão, como o coeficiente de determinação (
�
2
R 
2
 ), erro médio absoluto (MAE) ou erro médio quadrático (MSE). A interpretação dos resultados foi realizada com base nas métricas escolhidas.

Etapa 7: Inferência e Interpretação:
Com o modelo treinado, inferências foram feitas sobre a relação entre as variáveis. Os coeficientes da regressão foram analisados para entender o impacto relativo de cada variável independente na variável dependente.

Conclusão:
A conclusão do projeto envolveu a síntese de resultados, a comunicação de insights e a reflexão sobre a eficácia do modelo. Questões como a interpretabilidade do modelo e sua aplicabilidade prática foram consideradas.

Lições Aprendidas e Próximos Passos:
Finalmente, foram identificadas lições aprendidas durante o projeto e propostos possíveis próximos passos, como a exploração de técnicas mais avançadas, melhoria na qualidade dos dados ou expansão do escopo do modelo para lidar com relações não-lineares.
