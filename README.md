# Projeto 01 - Concessão de Cartões de Crédito

A descrição abaixo é referente ao meu primeiro projeto realizado no curso profissionalizante Cientista de Dados da EBAC. 

## Objetivo
Este projeto tem como objetivo desenvolver um modelo preditivo para avaliar o risco de inadimplência na concessão de cartões de crédito, utilizando uma base de dados disponível no Kaggle.

## Etapas do CRISP-DM

1. **Entendimento do Negócio**  
   Nesta fase, identificamos que o objetivo é auxiliar clientes a tomarem decisões informadas sobre crédito. O foco é prever o risco de inadimplência, caracterizado por atrasos superiores a 90 dias em um horizonte de 12 meses.

2. **Entendimento dos Dados**  
   Analisamos a base de dados, que contém informações demográficas e financeiras dos proponentes, como sexo, posse de veículo, educação, idade, tempo de emprego e histórico de crédito. Essa etapa é crucial para entender a estrutura e as características das variáveis.

3. **Preparação dos Dados**  
   Nesta etapa, realizamos a limpeza dos dados e a conversão de variáveis categóricas em variáveis dummy. Identificamos que não havia dados faltantes. Variáveis como sexo e tipo de renda foram transformadas para facilitar a modelagem.

4. **Modelagem**  
   Optamos por utilizar o algoritmo de Random Forest, que é robusto e eficaz para problemas de classificação. Dividimos os dados em conjuntos de treinamento e teste, treinando o modelo com a base de treinamento e avaliando sua performance com a base de teste.

5. **Avaliação**  
   Calculamos a acurácia do modelo, que atingiu mais de 97% de precisão. A matriz de confusão foi gerada para entender a classificação de bons e maus pagadores, permitindo visualizar os acertos e erros do modelo.

6. **Implantação**  
   Apontamento da importância de implementar o modelo em um sistema de crédito automatizado, onde decisões rápidas podem ser tomadas para aprovar ou rejeitar pedidos, minimizando riscos para a instituição financeira.

## Tecnologias Utilizadas
- Python
- Pandas
- Seaborn
- Scikit-Learn
