# Aprendizado de Máquina | Prof. Clávison Zapelini

## Avaliação 2
- Extração de características de sons
- Classificação com Perceptron Multi Camadas

### 1 – Extração de características de Som
- Desenvolva um programa para realizar extração de características de sons (conforme apresentado sugestões de pesquisa em aula – 20/10/2020).
- O programa deve ser capaz de analisar um dataset de audios e criar um arquivo *.arff com as características de todos os áudios contidos no dataset.
- Para geração do arquivo e demais etapas do trabalho, você deverá utilizar o dataset disponível em: https://www.kaggle.com/mmoreaux/audio-cats-and-dogs
- O dataset possui áudios (formato wav) com sons de cães e gatos, já separados em um conjunto para treinamento e outro conjunto para testes.
- As características que serão extraídas de cada som devem ser definidas por você.

### 2 – Seleção de um áudio e exibição das características
- O programa deve possibilitar selecionar um áudio qualquer, e exibir as características do áudio selecionado

### 3 – Classificação utilizando RNA (Perceptron Multicamada)
- O programa deve permitir que seja selecionado um áudio para realizar a inferência das probabilidades do áudio selecionado de ser de um cão ou de um gato (utilizar os áudios que estão separados para testes).
- A classificação deve ser feita com um Rede Neural Artificial (Perceptron Muilticamada), com os parâmetros Taxa de aprendizagem (learning rate) e Ciclos de treinamento (trainning time) podendo ser configurados em tempo de execução.

### 4 – O que entregar
- Compactar em um arquivo com o seu nome (em caso de dupla o nome de ambos alunos):
- Documento contendo quais características do áudio que foram escolhidas para a etapa de extração de características.
- Arquivo *.arff com as características extraídas
- Documento contendo as informações de todos os parâmetros utilizados na definição da RNA (momentum, quantidade de camadas ocultas, quantidade de neurônios de cada camada, taxa de aprendizagem e ciclos de treinamento)
- Código-fonte do extrator de características e do classificador (pode ser um link para o github)

### 5 – Data de entrega
- 03/11/2020 até as 23:59h
