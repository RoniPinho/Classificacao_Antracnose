#  Detecção de Antracnose em Folhas de Pequizeiro Usando Redes Neurais Convolucionais

Este projeto visa a **detecção automatizada** da **Antracnose** (*Colletotrichum acutatum*) em folhas de **Pequizeiro** (uma espécie nativa do Brasil) utilizando o poder do **Aprendizado Profundo** e **Redes Neurais Convolucionais (RNC)**.

A ocorrência de doenças em espécies nativas, como a Antracnose no pequizeiro, pode **comprometer significativamente a produção** e a produtividade das culturas. A detecção precoce e precisa é **crucial** para o manejo agrícola eficaz.

---

##  Visão Geral do Projeto

Este trabalho avaliou e comparou o desempenho de três arquiteturas populares de Redes Neurais Convolucionais para a tarefa de **classificação de imagens** de folhas de pequizeiro, distinguindo entre folhas **saudáveis** e folhas afetadas pela **Antracnose**.

As arquiteturas de RNC avaliadas foram:

* **LeNet**
* **MobileNet**
* **InceptionNet (GoogleNet)**

---

##  Conjunto de Dados

As imagens de folhas de pequizeiro utilizadas para o treinamento e avaliação foram coletadas no município de **Bonito de Minas**, localizado na região norte de Minas Gerais.

O **Dataset** utilizado no projeto pode ser acessado e verificado no link abaixo:

[Dataset - Imagens de Folhas de Pequizeiro](https://drive.google.com/drive/folders/1NHGxj_xCE8-aY43goh-MV26bJSdAR6qf?usp=sharing)

---

##  Avaliação de Desempenho

Os modelos de RNC foram avaliados utilizando as seguintes **métricas de desempenho**:

* **Acurácia:** Proporção de classificações corretas em relação ao total de amostras.
* **Precisão (Precision):** Capacidade do modelo de evitar falsos positivos (quão relevante é o resultado quando o modelo diz que há doença).
* **Sensibilidade (Recall/True Positive Rate):** Capacidade do modelo de encontrar todos os casos positivos (a taxa de detecção correta de doença).
* **Especificidade (True Negative Rate):** Capacidade do modelo de evitar falsos negativos (a taxa de identificação correta de folhas saudáveis).

---
