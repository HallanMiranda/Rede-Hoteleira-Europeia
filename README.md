# Rede Hoteleira - Projeto de classificação

#  * 4º Edição Hackday Comunidade DS

Nos dias 25 e 26 de março de 2023, a Comunidade DS promoveu um evento Hackday com uma competição de aprendizado de máquina (https://www.kaggle.com/competitions/cdshackdays4).
Este repositório contém notebooks e o modelo final desenvolvido pela equipe.

### 1. Problema de Negócio.

Em uma rede hoteleira  localizada no continente Europeu está preocupada com a crescente taxa de cancelamento após pandemias.
A gerencia deseja saber o motivo pelo qual os clientes estão cada vez mais cancelando suas reservas e entender o que pode ter mudado no comportamento dos clientes.

####  O desafio: 
Construir um modelo de aprendizado de máquina para prever se a reserva será cancelada ou não e obter o melhor desempenho.
Métrica de Desempenho: F1-Score

### 2. Os Dados
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
    * Regressão Linear
    * Random Forest Regressor
    * XGBoost Regressor
   

### 5. Desempenho do Modelo
Desempenho final:
    * F1 Score: 0.91217

    
### 6. Ganhos Financeiros

* Assumindo que uma diaria da categoria mais frequente em um Hotel em Madrid para duas pessoas que sao as categorias maus frequentes:
   - Categoria 4 estrelas custa R$ 1.224 por diária.
   - Categoria 5 estrelas custa R$ 2.057 por diária.
   - Portanto,o preço médio seria de aproximadamente R$ 1.640,50 por diária.
* De acordo com minha base de dados, 63% dos clientes nao cancelam suas reservas e 37% dos clientes cancelam.
* Assumindo que temos 300 quartos.
  
* <b>Faturamento máximo por Mês</b> 300 quartos x 30 dias x R$1.640,50 = 14,7 milhoes (Faturaria)
* <b>Faturamento Desperdiçado por Mês</b>
  - Clientes que cancelam por mês: 300 X 0.37 = 111
  - Faturamento desperdiçado = 111 × R$ 1.640,50 × 30 = R$ 5,13 milhoes
*
* Assumindo que cada cliente que iria cancelar, o time de marketing consiga reter ou vender a passagem para outro cliente em 80% dos casos teriasmos:
  
  * Para o algoritmo Baseline com 67% de acurácia:
     * 0.67 × 5.13 × 0.8 ≈ 2,19 Milhoēs/mês
       
  * Para o algoritmo alcançado com 91% de acurácia:
     * 0.91 × 5.13 × 0.8 ≈ 3.5 Milhoēs/Mês
       
  Esses cálculos representam o impacto do faturamento desperdiçado, considerando a acurácia do algoritmo.
  O aumento na acurácia do algoritmo de 67% para 91% resulta em uma redução do faturamento desperdiçado de aproximadamente R$ 2.1 para R$ 3.5 Milhoēs.
  Isso destaca como melhorar a precisão do modelo pode impactar positivamente o negócio, reduzindo as perdas devido a cancelamentos.
    
### 7. Conclusão. 
A equipe desenvolveu um modelo final que utilizou as previsões dos modelos XGBoost e Random Forest Classifier. Esse modelo alcançou uma pontuação F1 de 0.91217. 
Com base nesses resultados, é possível afirmar que o modelo desenvolvido pode ser muito útil para a Costa del Data na previsão de cancelamentos de reservas de hotéis. 
Com essa previsão antecipada, a rede poderá tomar ações preventivas para minimizar o impacto dessas ocorrências.

## 8. Próximos Passos.
Existem vários passos adicionais que poderiam ser aplicados ao projeto. Alguns deles listados abaixo

    * Realizar uma análise mais profunda dos dados.
    * Juntar dados de treinamento e teste e treinar o modelo novamente antes da submissão.
    * Aplicar um Implementar a validação cruzada.
    * Experimentar pesos diferentes no sistema de votação do modelo de conjunto.

### Referências:
    * Conjuntos de Dados de Avaliação de Cancelamento da Rede Hoteleira de Kaggle
    * Blog Seja um Data Scientist.
