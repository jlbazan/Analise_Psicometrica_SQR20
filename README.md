# Análise Psicométrica SQR-20

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
