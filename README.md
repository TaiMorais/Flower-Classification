# Classificação de Flores usando o Oxford Flowers 102 🌸

Este projeto tem como objetivo desenvolver um modelo de deep learning para classificar 102 diferentes espécies de flores utilizando o dataset Oxford Flowers. O foco está na aplicação de redes neurais convolucionais (CNNs) para classificação de imagens e na melhoria do desempenho do modelo por meio de técnicas como ajuste de hiperparâmetros, aumento de dados e otimização da arquitetura do modelo.

## Principais Funcionalidades:
- **Dataset**: Oxford Flowers 102, contendo 8.189 imagens distribuídas em 102 espécies de flores.
- **Arquitetura do Modelo**: Modelo baseado em CNN implementado com TensorFlow/Keras.
- **Melhorias de Desempenho**: Técnicas como regularização, aumento de dados e ajuste de hiperparâmetros foram aplicadas para melhorar a acurácia.
- **Avaliação**: Métricas como Hamming Loss e acurácia foram utilizadas para avaliar o desempenho do modelo.

## Resultados:
Atualmente, estou em processo de desenvolvimento e otimização do código. A otimização dos hiperparâmetros, que são os parâmetros do modelo que não são ajustados durante o treinamento, mas que podem impactar significativamente o resultado final, está em andamento. Para isso, utilizei uma técnica chamada Grid Search, que consiste em testar várias combinações de valores para esses hiperparâmetros, como a taxa de aprendizado, número de neurônios e camadas, a fim de identificar a melhor combinação possível.

Além disso, para garantir que os resultados sejam consistentes e não dependam de uma única divisão do dataset, apliquei o Cross-Validation com k-fold. Nessa técnica, o dataset é dividido em k partes, e o modelo é treinado k vezes, cada vez utilizando uma dessas partes para validação e as outras para treinamento. Essa abordagem ajuda a reduzir o risco de overfitting, que é quando o modelo se ajusta tão bem aos dados de treinamento que perde a capacidade de generalizar para novos dados, além de garantir que o modelo funcione bem em diferentes subconjuntos dos dados.

Essa combinação do Grid Search com o Cross-Validation está sendo implementada para melhorar ainda mais o desempenho do modelo.
