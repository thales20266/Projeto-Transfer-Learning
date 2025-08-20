# Projeto-Transfer-Learning
Projeto de Transfer-Learning feito para o BootCamp da BairesDev na DIO

Classificador de Imagens com Transfer Learning

Este projeto é um classificador de imagens que utiliza Machine Learning e Transfer Learning para diferenciar imagens de gatos e cachorros. Ele compara uma rede neural treinada do zero com um modelo pré-treinado (VGG16) adaptado para o nosso dataset, demonstrando o poder do Transfer Learning em datasets pequenos.

O projeto foi desenvolvido durante o bootcamp de Machine Learning da BairesDev em parceria com a DIO, sob a orientação do Professor Doutor Diego Renan Bruno.

🚀 Funcionalidades

Treinamento de uma rede neural do zero com dataset limitado

Treinamento de um modelo pré-treinado VGG16 com Transfer Learning

Comparação da acurácia entre os dois métodos

Normalização e pré-processamento das imagens

Códigos disponíveis em inglês (original) e português (traduzido e comentado)

Visualização de gráficos de loss e acurácia durante o treinamento

📊 Resultados

Rede neural do zero: ~63% de acurácia no conjunto de teste

Transfer Learning com VGG16: ~88% de acurácia no conjunto de teste

Os gráficos gerados pelo código permitem comparar visualmente a evolução da loss e da acurácia durante o treinamento das duas redes.

🛠 Tecnologias

Python 3

TensorFlow / Keras

NumPy

Matplotlib

⚡ Como usar

Faça o download do dataset Cats & Dogs
 ou use o seu próprio dataset.

Extraia as imagens na pasta data/.

Abra o notebook code_pt.ipynb ou code_en.ipynb.

Execute as células passo a passo para treinar os modelos e visualizar os resultados.

Dica: O notebook já faz a divisão automática entre treinamento, validação e teste, além de normalizar e pré-processar as imagens.

💡 Aprendizados

Como aproveitar modelos pré-treinados para acelerar o aprendizado em datasets pequenos

Importância de técnicas de regularização, como dropout

Diferença de performance entre treinar uma rede do zero e usar Transfer Learning
