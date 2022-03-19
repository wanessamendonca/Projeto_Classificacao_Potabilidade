# Previsão de Potabilidade da Água com Base em Características Físico-Químicas  

<img src = 'https://user-images.githubusercontent.com/92948655/157529363-846164ce-1ece-402f-9002-09158875a518.png' width="500">

*Fonte da Imagem: The Guardian*

## Contexto e Objetivo do Projeto

Dados publicados pela Organização Mundial de Saúde (OMS) em parceria com a UNICEF mostraram que em 2017 cerca de 884 milhões de pessoas não tinham acesso a água segura para beber. A falta de acesso à água potável pode levar ao desenvolvimento de quadros de saúde relacionados a diarreia, cólera, febre tifóide e doenças tropicais. 

Para que haja superação deste cenário e o objetivo de desenvolvimento sustentável proposto pelas Nações Unidas que diz respeito ao acesso universal à água e ao saneamento básico seguros possa ser alcançado, estima-se que cerca de 2,2 bilhões de pessoas devem ter acesso garantido a água potável até 2030.

**Tendo em vista o contexto apresentado, este projeto tem por objetivo a proposição de um modelo de machine-learning capaz de classificar uma fonte de água como sendo ou não potável e portanto, apropriada para o consumo, com base em suas características físico-químicas.**

🎲 Os dados utilizados para a implementação e geração do modelo foram retirados diretamente da plataforma Kaggle e podem ser acessados por meio deste [link](https://www.kaggle.com/adityakadiwal/water-potability). O conjunto de dados estava em sua terceira versão (de 25 de abril de 2021).

🔍 Para maiores informações a respeito do contexto apresentado, acesse a página do Centro para Controle e Prevenção de Doenças dos Estados Unidos (CDC) disponível [aqui](https://www.cdc.gov/healthywater/global/wash_statistics.html#:~:text=An%20estimated%202.2%20billion%20people,access%20to%20safely%20managed%20sanitation.).

## Dicionário de Dados

<img src = https://user-images.githubusercontent.com/92948655/156599810-6135eead-7d22-4c29-96e4-038dd2e5a4a0.png width="650">

## Headlines

• O principal objetivo do projeto foi alcançado: vários modelos foram propostos para a previsão de potabilidade da água com base em características físico-químicas. Dentre estes, aquele que apresentou um melhor equilíbrio entre acurácia e especificidade foi aquele utilizou um algoritmo SVC com função de base radial;

• De forma geral, modelos com diferentes técnicas apresentaram resultados de acurácia e especificidade bastante similares entre si: 0.64 e 0.93, respectivamente, em média;

• Por meio de distribuições foi possível observar que as amostras de água potáveis e não-potáveis apresentam características similares, portanto para diferenciá-las e classificá-las corretamente, o uso de uma técnica mais sofisticada e que seja sensível a sutis diferenças se faz bastante válido;

• Os modelos apresentaram acurácia mediana, mas se saíram muito bem em termos de especificidade, ou seja, na previsão de verdadeiros negativos, o que neste projeto pode ser traduzido como fontes de água não-potáveis;

• Por outro lado, os modelos no geral se saíram muito mal em termos de sensibilidade ou previsão de verdadeiros positivos, desperdiçando fontes de água que são potáveis ao classificá-las como inapropriadas;

• Dentre todas as variáveis, ficou constatado que aquelas que possuem maior nível de influência na classificação das amostras são a turbidez, a condutividade, o nível de sulfatos e a quantidade de sólidos.
