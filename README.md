# anomaly-classifier

Classificação Preditiva de Dados Anonimizados
Este projeto apresenta uma análise comparativa de algoritmos de aprendizado supervisionado aplicados a um conjunto de dados anonimizados.
O desafio central consistiu em identificar padrões na TARGET CLASS sem o suporte de conhecimento prévio do domínio (domínio desconhecido), 
exigindo um foco rigoroso em estatística, pré-processamento e otimização de hiperparâmetros.

🎯 Objetivo
Desenvolver um classificador robusto capaz de maximizar a precisão preditiva, superando os desafios impostos pela ausência de significado semântico nas variáveis de entrada.

🛠 Metodologia
O pipeline de desenvolvimento seguiu as seguintes etapas:

Limpeza e Engenharia: Identificação e remoção de variáveis com baixo poder preditivo (MGJM, HYKR, GUUB).

Seleção de Modelos: Comparação entre K-Nearest Neighbors (KNN) e Random Forest.

Otimização: Uso de GridSearchCV para refinamento dos hiperparâmetros do KNN, visando o equilíbrio entre as classes.

📊 Principais ResultadosModeloAcuráciaDestaqueKNN (Otimizado)77%Eliminação de vieses entre classesRandom Forest78%Melhor robustez e performance global💡 
ConclusãoA análise demonstrou que modelos baseados em árvores, como o Random Forest, são mais eficazes para este dataset. 
Isso sugere a existência de relações não-lineares complexas entre as variáveis anonimizadas, as quais o Random Forest captura com maior eficiência do que algoritmos baseados puramente em métricas de distância (como o KNN).🚀
Tecnologias UtilizadasPython 3Scikit-Learn (KNN, Random Forest, GridSearchCV)Pandas & NumPy
