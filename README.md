# Rede Hoteleira Européia - Projeto de classificação

#  * Hackday 4ª Edição Comunidade DS

Nos dias 25 e 26 de março de 2023, a Comunidade DS promoveu um evento Hackday com uma competição de aprendizado de máquina (https://www.kaggle.com/competitions/cdshackdays4).
Este repositório contém notebooks e o modelo final desenvolvido pela equipe.

### 1. Problema de Negócio.

Em uma rede hoteleira  localizada no continente Europeu está preocupada com a crescente taxa de cancelamento após pandemias.
A gerencia deseja saber o motivo pelo qual os clientes estão cada vez mais cancelando suas reservas e entender o que pode ter mudado no comportamento dos clientes.

####  O desafio: 
Construir um modelo de aprendizado de máquina para prever se a reserva será cancelada ou não e obter o melhor desempenho.
Métrica de Desempenho: F1-Score

### 2. Dados
Os conjuntos de dados usados na competição podem ser encontrados em https://www.kaggle.com/competitions/cdshackdays4/data
### 3. Estratégia de Solução

### 1. Realizar uma rápida leitura dos dados e fazer a execução, seguindo a estrutura:
    * Análise de descrição de dados
    * Engenharia de recursos
    * Filtragem de Dados
    * Seleção de recursos
    * Modelagem de aprendizado de máquina
    * Entender o desempenho do modelo
    * Enviar previsões para a competição do Kaggle
    2. Testar diferentes métodos de codificação e modelos de aprendizado de máquina.
    3. Ajustar parâmetros do modelo.
    
### 4. Ferramentas e modelos de aprendizado de máquina
    * Python 3.11.2
    * Regressão Linear
    * SVM
    * Aumento de Gradiente
    * Random Forest Regressor
    * XGBoost Regressor
    * seletor de recursos  Boruta

### 5. Desempenho dos Modelos
Desempenho final:
    * F1 Score: 0.95612
    
##  6. Conclusão.
A equipe desenvolveu um modelo final que utilizou as previsões dos modelos XGBoost, Gradient Boosting e Random Forest Classifier. Esse modelo alcançou uma pontuação F1 de 0,95612 e conquistou a quinta posição na competição. Com base nesses resultados, é possível afirmar que o modelo desenvolvido pode ser muito útil para a Costa del Data na previsão de cancelamentos de reservas de hotéis. Com essa previsão antecipada, a rede poderá tomar ações preventivas para minimizar o impacto dessas ocorrências.

## 7. Próximos Passos.
Existem vários passos adicionais que poderiam ser aplicados ao projeto. Alguns deles listados abaixo:
    * Realizar uma análise mais profunda dos dados.
    * Juntar dados de treinamento e teste e treinar o modelo novamente antes da submissão.
    * Aplicar um Implementar a validação cruzada.
    * Testar mais modelos de aprendizado de máquina (como o KNN).
    * Experimentar pesos diferentes no sistema de votação do modelo de conjunto.

### Referências:
    * Conjuntos de Dados de Avaliação de Cancelamento da Rede Hoteleira de Kaggle
    * Blog Seja um Data Scientist
