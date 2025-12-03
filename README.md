Detecção de Antracnose em Folhas de Pequizeiro Usando Redes Neurais Convolucionais
Este projeto visa a detecção automatizada da Antracnose (Colletotrichum acutatum) em folhas de Pequizeiro (uma espécie nativa do Brasil) utilizando o poder do Aprendizado Profundo e Redes Neurais Convolucionais (RNC).
A ocorrência de doenças em espécies nativas, como a Antracnose no pequizeiro, pode comprometer significativamente a produção e a produtividade das culturas. A detecção precoce e precisa é crucial para o manejo agrícola eficaz.
Visão Geral do Projeto
Este trabalho avaliou e comparou o desempenho de três arquiteturas populares de Redes Neurais Convolucionais para a tarefa de classificação de imagens de folhas de pequizeiro, distinguindo entre folhas saudáveis e folhas afetadas pela Antracnose.
As arquiteturas avaliadas foram:
•	LeNet
•	MobileNet
•	InceptionNet (GoogleNet)
 Conjunto de Dados
As imagens de folhas de pequizeiro utilizadas para o treinamento e avaliação foram coletadas no município de Bonito de Minas, localizado na região norte de Minas Gerais.
Dataset utilizado pode ser verificado no link abaixo:

https://drive.google.com/drive/folders/1NHGxj_xCE8-aY43goh-MV26bJSdAR6qf?usp=sharing


Avaliação de Desempenho
Os modelos foram avaliados utilizando as seguintes métricas de desempenho:

Acurácia: Proporção de classificações corretas em relação ao total.

Precisão (Precision): Capacidade do modelo de evitar falsos positivos (quão relevante é o resultado).

Sensibilidade (Recall/True Positive Rate): Capacidade do modelo de encontrar todos os casos positivos (detecção de doença).

Especificidade (True Negative Rate): Capacidade do modelo de evitar falsos negativos (detecção de folhas saudáveis).
