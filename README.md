**1. Título do projeto**

Aplicação de Machine Learning e Deep Learning na base de dados Breast Cancer

**2. Objetivo do projeto**

Este projeto teve como objetivo prever a partir das variáveis estudadas se o câncer dos pacientes era benigno ou maligno. 

**3. Base de Dados**

O conjunto de dados utilizado neste Projeto está disponível em no caminho [https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html). O dataset possui 569 linhas e 31 features. Cabe ressaltar que o dataset não possui dados nulos, não sendo assim necessário realizar a etapa de remoção ou preechimento dos valores ausentes.

**4. Algoritmo utilizado**

Para este trabalho, a ideia foi avaliar a base x previsão de câncer maligno nos pacientes em avaliação sob 3 visões, uma utilizando Machine Learning através do método de Regressão Logística (escolha aleatória), outra utilizando Deep Learning (Redes Neurais) e uma terceira utilizando o Pycaret, uma biblioteca poderosa que permite que o Cientista de Dados em poucas linhas de código avalie a performance do modelo desenvolvido.

**5. Estrutura do Projeto**

Para realizar a classificação nas 3 visões avaliadas (ML - Regressão Logística, DP - Redes Neurais e Pycaret), em linhas gerais, percorri as etapas mais comuns em um Projeto de Data Science, como importação e análise exploratória dos dados, pré-processamento e divisão das bases em treino e teste, modelagem, avaliação da performance do modelo, deploy do modelo e realização de novas previsões.

**6. Conclusões e Próximos Passos**

Após avaliar as 3 visões, alguns pontos chamaram a atenção, são eles:

- De fato a biblioteca Pycaret vem para facilitar a vida do Cientista de Dados no que se refere a Machine Learning, pois em poucas linhas de código, é apresentado  um comparativo de performance dos modelos de classificação disponíveis, afim de permitir ao Cientista de Dados selecionar o que melhor se enquadra ao desafio, enquanto na modelagem tradicional, seria necessário rodar o projeto mais de uma vez comparando os resultados afim de escolher o melhor modelo. Neste sentido, prototipagem e testes se tornam mais ágeis com o Pycaret.
*  Percebe-se ainda que de fato Redes Neurais tendem a entregar uma melhor performance em detrimento dos modelos de Machine Learning, mesmo em bases pequenas como a deste estudo. No entanto, é sabido que o processamento dos dados via Redes Neurais é mais pesado do via modelagem tradicional, desse modo, cabe uma avaliação se o esforço x tempo de processamento dado o tamanho da base necessita de uma modelagem via Redes Neurais, ou se para a demanda mapeada a modelagem tradicional já seria suficiente.


Contribuições: Se você deseja contribuir para este projeto, fique a vontade para criar uma cópia e realizar as melhorias !
