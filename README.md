# Problema-de-Classificacao
Trabalho final da matéria de Data Mining na Pós Graduação em BI-Master na PUC-RJ

## Trabalho Proposto

- A partir de uma base de dados de treino com informações sobre o estado de saúde de Cavalos, desenvolver e treinar um Modelo Preditivo para indicar se o cavalo Morreu, Sobreviveu ou foi submetido à Eutanásia

- Foi fornecida uma base de treino com 27 atributos numéricos e categóricos que descrevem o estado de saúde de cavalos. Cada registro da base corresponde a um cavalo

- Cada registro da base de treino apresenta campo com a "classe" a ser prevista : cavalo Morreu, Sobreviveu ou foi submetido à Eutanásia

- Foi fornecida, também, base de testes para aplicação do modelo treinado e avaliação dos resultados

### Arquivos
DESCREVER OS ARQUIVOS 

## Resumo do Trabalho Desenvolvido
- O trabalho foi desenvolvido em RapidMiner
- Foi desenvolvida solução para aplicação de Oversample usando os operadores do RapidMiner
- Dentre as simulações realizadas a que proporcionou o melhor desempenho conta com a aplicação das seguintes técnicas:
  - Tratamento de Missing Values 
  - Retirada de Atributos com muitos Missing Values (redução de dimensionalidade / análise exploratória dos dados)
  - Balanceamento de Dados (OverSample)
  - Seleção de atributos por peso (Weight by Information Gain / redução de dimensionalidade) 
  - Retirada de Outliers 
  - Aplicação do Modelo Gradient Boosted Trees 

- O melhor desempenho obtido teve Acurácia de 98,88% e Kappa de 0,98
- Somente 1 registro da base de teste foi classificado com erro na simulação em que obtive o melhor desempenho
 
- Apresento nas próximas páginas o relatório detalhando cronologicamente os experimentos realizados

