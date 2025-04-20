# Análise Psicométrica da escala de rastreio SQR-20 usando dados do GAPSI e Apoia USP

**Gabriela Amaral<sup>1</sup>, Brunna Quatrochi<sup>1</sup>, Jorge L. Bazán <sup>2</sup> and Emanuela Pap da Silva <sup>3</sup>**

<sup>1</sup>Departamento de Matemática Aplicada e Estatística,
<sup>2</sup>Bacharelado em Estatística e Ciencia de Dados,
<sup>3</sup>Serviço de Promoção Social
Universidade de São Paulo, São Carlos, Brasil


**Autor de contato:** Jorge L. Bazán, jlbazan@icmc.usp.br


## Resumo
 Neste notebook, é realizada uma análise psicométrica da escala de rastreamento SRQ-20, composta por vinte
 itens dicotômicos que avaliam indicadores de transtornos mentais comuns (TMC), com respostas “sim” ou
 “não”. Foram utilizadas bases de dados dos anos de 2021, 2022 e 2023, obtidas por meio de questionários
 aplicados pela GAPSI e Apoia USP, que são serviços de apoio psicossocial à saúde mental da comunidade
 universitária da USP, campus de São Carlos, respondidos por alunos de graduação deste campus. Os re
sultados indicam que o teste é confiável e unidimensional, e os escores do TMC podem ser obtidos tanto
 pela teoria clássica dos testes quanto pelo modelo de dois parâmetros da teoria da resposta ao item (TRI).
 O modelo TRI de dois parâmetros foi escolhido como o melhor modelo para reportar os escores do TMC
 que medem o sofrimento mental. No modelo escolhido, os itens são caracterizados pelos parâmetros de
 dificuldade e discriminação. A dificuldade de um item pode ser interpretada como a gravidade do sintoma
 abordado pela questão, enquanto o parâmetro de discriminação mede a eficácia do item em diferenciar re
spondentes com diferentes níveis de sofrimento mental avaliado. Uma avaliação do modelo foi realizada, e os
 resultados foram salvos. A análise realizada neste estudo permitiu identificar as características psicométricas
 dos itens, oferecendo uma compreensão mais aprofundada das propriedades do instrumento e sua adequação
 para avaliar a saúde mental dos estudantes.
 Introdução
 
## Instalação dos pacotes do R

Antes de rodar os códigos em sua máquina, garanta que os pacotes necessários do R estão devidamente instalados. Para instalar os pacotes, rode o seguinte código no seu ambiente R:

```
install.packages("ggplot2") 
install.packages("readxl") 
install.packages("foreign")
install.packages("ltm")
install.packages("mirt")
install.packages("psych")
install.packages("psychometric")
install.packages("irtoys")
install.packages("mirtCAT")
install.packages("openxlsx")
```
## Como citar este trabalho

Amaral, G., Quatrochi, B., Bazán, J. L and da Pap da Silva, E. (2025). Análise Psicométrica da escala de rastreio SQR-20 usando dados do GAPSI e Apoia USP. 
Version v1.0. DOI: https://doi.org/10.5281/zenodo.15246854

Se preferir, é possível incluir a seguinte entrada BibTeX:

@misc{amaraletal2025, <br>
author = {Gabriela Amaral and Brunna  Quatrochi and Jorge L. Bazán and Emanuela Pap da Silva},  <br>
title = {Análise Psicométrica da escala de rastreio SQR-20 usando dados do GAPSI e Apoia USP},  <br>
year = {2025},  <br>
version = {v1.0},
doi = {10.5281/zenodo.15246854}, <br>
url = {https://doi.org/10.5281/zenodo.15246854}, <br>
note = {Zenodo} <br>
} <br>
