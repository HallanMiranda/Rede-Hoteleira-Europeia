# Rede Hoteleira - Projeto de classificação

#  * 4º Edição Hackdays Comunidade DS

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

### 1. Realizar uma rápida leitura dos dados e fazer a execução, seguindo o ciclo de desenvolvimento para Data Science CRISP-DS:

    * Questão de Negócio
    * Entendimento do Negócio
    * Coleta de Dados
    * Limpeza dos Dados
    * Exploração dos Dados
    * Modelagem dos Dados
    * Algotitimos de Machne Learning
    * Avalição do Algotitimo
    * Modelo em produção
    * Enviar previsões para a competição do Kaggle
    
    2. Testar diferentes métodos de codificação e modelos de aprendizado de máquina.
    3. Ajustar parâmetros do modelo.
    
### 4. Ferramentas e modelos de aprendizado de máquina
    * Python 3.11.2
    * seletor de recursos Boruta
    * Regressão Linear
    * Random Forest Regressor
    * XGBoost Regressor
   

### 5. Desempenho dos Modelos
Desempenho final:
    * F1 Score: 0.91217
    
## 6. Conclusão.
A equipe desenvolveu um modelo final que utilizou as previsões dos modelos XGBoost e Random Forest Classifier. Esse modelo alcançou uma pontuação F1 de 0.91217. Com base nesses resultados, é possível afirmar que o modelo desenvolvido pode ser muito útil para a Costa del Data na previsão de cancelamentos de reservas de hotéis. Com essa previsão antecipada, a rede poderá tomar ações preventivas para minimizar o impacto dessas ocorrências.

## 7. Próximos Passos.
Existem vários passos adicionais que poderiam ser aplicados ao projeto. Alguns deles listados abaixo:

    * Realizar uma análise mais profunda dos dados.
    * Juntar dados de treinamento e teste e treinar o modelo novamente antes da submissão.
    * Aplicar um Implementar a validação cruzada.
    * Experimentar pesos diferentes no sistema de votação do modelo de conjunto.

### Referências:
    * Conjuntos de Dados de Avaliação de Cancelamento da Rede Hoteleira de Kaggle
    * Blog Seja um Data Scientist
