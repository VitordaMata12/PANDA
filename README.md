# PANDA

Classificação de Câncer de Mama – Comparando Regressão Logística e Random Forest
1. Descrição do Projeto

Este projeto tem como objetivo aplicar e comparar dois modelos de classificação supervisionada: Regressão Logística e Random Forest.

Foi utilizado o dataset Breast Cancer Wisconsin, disponível na biblioteca scikit-learn. O problema consiste em prever se um tumor é maligno (0) ou benigno (1) a partir de medidas extraídas de exames laboratoriais.

2. Dataset

Nome: Breast Cancer Wisconsin (Diagnostic)

Fonte: sklearn.datasets.load_breast_cancer()

Instâncias: 569 amostras

Atributos: 30 variáveis numéricas relacionadas a características de células (ex: raio, textura, suavidade).

Classes:

0 → Maligno

1 → Benigno

3. Modelos Treinados

Foram utilizados dois modelos de classificação:

Regressão Logística

Modelo linear simples, rápido e interpretável.

Necessita normalização dos dados.

Random Forest

4. Resultados Obtidos 
| Modelo              | Acurácia | Precisão | Recall | F1-Score |
| ------------------- | -------- | -------- | ------ | -------- |
| Regressão Logística | \~0.95   | \~0.96   | \~0.97 | \~0.96   |
| Random Forest       | \~0.96   | \~0.97   | \~0.98 | \~0.98   |

5. Conclusão

A Regressão Logística apresentou bons resultados, com cerca de 95% de acurácia, sendo simples e eficiente.

O Random Forest teve desempenho ligeiramente superior, atingindo até 98% no F1-Score, mostrando melhor equilíbrio entre precisão e recall.

 Portanto, o Random Forest foi o melhor modelo neste caso, pois identificou mais tumores corretamente sem aumentar os falsos positivos.


Conjunto de várias árvores de decisão.

Mais robusto e capaz de capturar relações não lineares.
