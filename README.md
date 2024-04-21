Projeto 01 - Concessão de cartões de crédito
Índice
Etapa 1 CRISP - DM: Entendimento do negócio
Etapa 2 & 3 Crisp-DM: Entendimento e preparação dos dados
Import das bibliotecas/pacotes
Leitura e pré-processamento dos dados
Entendimento dos dados - Análise univariada
Gráficos de barras
Histogramas
Entendimento dos dados - Análise bivariada
Quantidade de categorias por variável
Conversão das variáveis categóricas em variáveis numéricas (dummies)
Etapa 4 e 5 Crisp-DM: Modelagem & Avaliação dos resultados
Dividindo a base em treino e teste
RandomForestClassifier
DecisionTreeClassifier #1
DecisionTreeClassifier #2
Etapa 6 Crisp-DM: Implantação
Etapa 1 CRISP - DM: Entendimento do negócio
Este é um problema de concessão de cartões de crédito, publicado no Kaggle, uma plataforma que promove desafios de ciência de dados, oferecendo prêmios em dinheiro para os melhores colocados. O link original está aqui.

Essa é uma base de proponentes de cartão de crédito. O objetivo é construir um modelo preditivo para identificar o risco de inadimplência (tipicamente definida pela ocorrência de um atraso maior ou igual a 90 em um horizonte de 12 meses) através de variáveis que podem ser observadas na data da avaliação do crédito (tipicamente quando o cliente solicita o cartão).

Atividades do CRISP-DM:

Objetivos do negócio
Objetivos da modelagem
O objetivo está bem definido: desenvolver o melhor modelo preditivo de modo a auxiliar o mutuário a tomar suas próprias decisões referentes a crédito.

Note que o objetivo aqui é que o modelo sirva o mutuário (o cliente) para que avalie suas próprias decisões, e não a instituição de crédito.

