# Machine-Learning-MVP
MPV para disciplina de Machine Learning e Analytics - PUC-RIO - Matheus Assis

# 🚗 Previsão de Preços de Carros Usados com Machine Learning

Este projeto foi desenvolvido como parte do MVP da disciplina de Ciência de Dados. O objetivo é prever o preço de venda de um carro usado com base em suas características, utilizando técnicas de aprendizado de máquina supervisionado.

## 📊 Dataset Utilizado

O dataset foi retirado do [Kaggle](https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho) e contém informações sobre veículos como:

- Ano de fabricação
- Quilometragem
- Tipo de combustível
- Tipo de vendedor
- Transmissão
- Preço de venda

O arquivo foi incluído neste repositório e é carregado diretamente via URL no notebook, garantindo reprodutibilidade.

## ❓ Perguntas que guiaram o projeto

- Quais características mais influenciam o preço de um carro usado?
- É possível prever o preço de venda com boa precisão usando modelos simples?
- Qual modelo de aprendizado de máquina se sai melhor nesse tipo de problema?
- Ajustar os hiperparâmetros melhora significativamente o desempenho?

## 🧠 Técnicas Utilizadas

- Regressão Linear (baseline)
- Random Forest (modelo principal)
- Otimização de hiperparâmetros com GridSearchCV
- Avaliação com métricas R² e RMSE
- Normalização e codificação de variáveis
- Feature engineering (idade do carro)

## 📁 Estrutura do repositório

- `car_price_prediction.ipynb`: notebook com todo o código e explicações
- `car_data.csv`: dataset utilizado no projeto
- `README.md`: este resumo do projeto

## ✅ Execução

Para rodar o notebook, basta abrir no Google Colab e executar todas as células. O dataset será carregado diretamente via URL do GitHub.

