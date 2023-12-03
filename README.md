# Caio Casagrande 👋🏼

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/caiopc) [![Portfólio de Dados](https://img.shields.io/badge/Portfólio%20de%20Dados-222222?style=for-the-badge&logo=GitHub%20Pages&logoColor=white)](https://caiocasagrande.github.io/portfolio/)

## Sobre mim
  
**Mestre em Economia Aplicada** pelo Programa de Pós-Graduação em Organizações e Mercados (PPGOM) e **Bacharel em Engenharia Agrícola** pela Universidade Federal de Pelotas (UFPel). Experiências profissionais em **Análise de Mercado** e **Análise de Negócios**. Base acadêmica com sólida formação em matemática, estatística e econometria ao longo dos anos, voltada à solução de problemas e fundamentada em dados.

Atualmente, estou buscando a oportunidade de trabalhar profissionalmente na área de dados e ajudar empresas a lidar com os processos de tomada de decisão de negócios.

## Habilidades Técnicas
- Linguagens de programação: Python, R, SQL
- Feature Engineering: Encoding, Scaling, Imputers, Resampling
- Machine Learning: Regressão, Classificação, Cross-Validation, Hyperparameter Tuning, Random Search
- Métricas: Confusion Matrix, Accuracy, Precision, Recall, F1 Score, MAE, MAPE, RMSE, R²
- Visualização: Power BI, Streamlit Dashboards
- Cloud: AWS (Glue, S3, Athena, SageMaker)
- Habilidades Profissionais: Inglês Avançado, Pacote Office


# Projetos

## 👖 [InStyle - Classificação de Clientes](https://github.com/caiocasagrande/instyle) ⭐
<sub>[lang:pt-BR]</sub>

- **Problema de Negócio:** A loja de moda InStyle é uma grande loja de roupas, mas enfrenta desafios significativos em relação à experiência do cliente. Em vista de que para aumentar as receitas de uma loja é necessário priorizar a satisfação dos clientes, a InStyle montou uma equipe com a tarefa de treinar um algoritmo para classificar os clientes, prevendo quais clientes ficarão Insatisfeitos e agir rápido para entender o motivo da insatisfação e reverter o cenário.

- **Objetivos:** Gerar insights através dos dados, produzir informações visuais sobre a base de clientes da empresa, classificar e identificar os clientes insatisfeitos através de um algoritmo de Machine Learning.

- **Conclusões:** A implementação do modelo de Machine Learning para classificar a satisfação do cliente na InStyle marca uma virada estratégica significativa. O foco na satisfação do cliente não apenas aborda desafios cruciais da empresa, mas também redefine a abordagem para aprimorar a experiência do cliente e consolidar sua posição no mercado de moda.

- **Benefícios Tangíveis:** elevação da satisfação do cliente, fidelização e retenção, direcionamento eficiente de marketing, otimização de custos e otimização do fluxo de trabalho.


## 📈 [Rossmann - Previsão de Vendas](https://github.com/caiocasagrande/rossmann) ⭐
<sub>[lang:en-US]</sub>

- **Problema de Negócio:** O CEO da rede de farmácias Rossmann planeja renovar as suas lojas pois a marca está passando por um *rebranding*, mas não sabe o quanto cada uma terá a disposição para investir nas reformas. 

- **Solução:** Vários modelos de Machine Learning foram testados a fim de prever o faturamento das lojas para as seis semanas seguintes.  com o objetivo de prever quanto dinheiro cada loja da Rossmann terá disponível para gastar em suas reformas.

- **Resultado:** Através de uma Análise Exploratória de Dados completa, a empresa obteve insights valiosos sobre os fatores que influenciam as vendas, fornecendo uma base sólida para a tomada de decisões. Em conclusão, este projeto entregou com sucesso um Modelo de Previsão de Vendas, a fim de otimizar a alocação de recursos para renovações de lojas Rossmann.

## 💳 [Score de Crédito](https://github.com/caiocasagrande/bank_credit_score)
<sub>[lang:en-US]</sub>

- **Sobre o Score de Crédito:** O Score de Crédito é um indicador de risco para um cliente, que pode ser utilizado para tomar decisoes de negócios. Vários fatores influenciam neste número, como o histórico do cliente, linhas de crédito abertas, valor total, etc. Alguns fatores para levar em consideração são: histórico de crédito limitado, tamanho da instituição financeira e a sua estratégia de mercado.

- **Objetivo:** Construir um modelo de risco interno a fim de otimizar a rentabilidade e a segurança do negócio. Porém, ao mesmo tempo, o banco pretende encontrar um <u>equilíbrio entre rentabilidade e expansão do mercado, alinhando-se com os seus objetivos estrategicos de um negócio em ascensão.</u>
    
- **Conclusão:** A análise dos decis da pontuação de crédito gerou *insights* importantes. Os decis 1, 2 e 3 de melhor desempenho são a escolha ideal para estratégias conservadoras de aprovação de empréstimos. O sexto decil surge como pico de rentabilidade, mas a exploração estratégica dos decis adjacentes proporciona oportunidades para maximizar *market-share*. O projeto é apresentado em um dashboard no Streamlit. 

- **Link para o Dashboard:** [StreamlitApp]([https://streamlit.io/](https://credit-scoring-bank-caio-casagrande.streamlit.app/))

## 🥷 [Detecção de Fraude](https://github.com/caiocasagrande/fraud_detection)
<sub>[lang:en-US]</sub>

- **A importância da deteção de fraude:** As repercussões da fraude vão além das perdas financeiras, incluindo danos à reputação, deterioração da confiança do cliente e possíveis ramificações legais. Ao implementar técnicas de Ciência de Dados, empresas podem melhorar sua capacidade de detectar e prevenir atividades fraudulentas, fortalecendo a instituição e preservando as operações.

- **Objetivo:** Construir um mecanismo de defesa para a instituição financeira fundamentado em técnicas de Ciência de Dados para fortalecer a infraestrutura de segurança e <u>elevar a precisão dos processos de tomada de decisão</u>. 

- **O projeto:** Um modelo de detecção de fraude com <u>Análise Exploratória de Dados</u>, preparação de dados com *Encoders*, *Scalers* e balanceamento de dados com SMOTE. Os modelos de *Machine Learning* testados foram: *Logistic Regression*, *Decision Tree Classifier* e *Random Forest Classifier*. O melhor modelo foi usado para buscar os melhores parâmetros com *RandomizedSearchCV*.

- **Resultado final:** Os melhores parâmetros foram utilizados para rodar o modelo novamente e retornaram os seguintes resultados: Acurácia: 0,9743, Precisão: 0,9662, Recall: 0,9828 e F1 Score: 0,9744. O alto resultado de Recall dá confiança para seguir com esse modelo nas próximas etapas do projeto da instituição financeira, identificando uma fraude quando necessário.

## 💵 [Elasticidade Preço da Demanda](https://github.com/caiocasagrande/price_elasticity_of_demand)
<sub>[lang:en-US]</sub>

- **Sobre Elasticidade Preço:** A análise emprega princípios fundamentais de elasticidade de preços para descobrir insights que possam orientar a tomada de decisões estratégicas. Este projeto demonstra a importância da modelagem econômica e da ciência de dados, oferecendo uma breve visão do valor potencial de tal análise para empresas que operam no mundo real.

- **Objetivo:** O objetivo é entender como as variações de preços impactam a demanda do consumidor por produtos elásticos. Assim, escolheu-se a categoria mais vendida da loja com mais vendas para aplicar a análise. 

- **Resultado:** O projeto conta com uma <u>Análise Exploratória de Dados</u> com vários *insights* e termina com uma tabela onde temos os nomes dos produtos, a renda que geram atualmente, a variação de faturamento que podem gerar em valores monetários e em porcentagem.

- **Link para o Dashboard:** [StreamlitApp](https://price-elasticity-caio-casagrande.streamlit.app/)

## 💳 [Score de Crédito](https://github.com/caiocasagrande/credit_score)
<sub>[lang:en-US]</sub>

- **O processo de Score de Crédito:** Uma pontuação de crédito é uma ferramenta crucial para instituições financeiras avaliarem seus clientes e a quantidade de dinheiro envolvida. A análise engloba vários fatores, como renda anual, situação de propriedade de casa própria, valor do empréstimo e taxa de juros cobrada.

- **Objetivo:** Executar uma análise de pontuação de crédito para aumentar a rentabilidade de um banco conservador. Para realizar esse projeto, o primeiro passo foi realizar uma <u>Análise Exploratória de Dados detalhada</u> para entendermos melhor a base de dados e como ela está distribuída. Após *Data Cleaning* e *Feature Engineering*, o projeto focou em implementar e comparar três modelos de *Machine Learning* para classificar os clientes em decis.

- **Resultado:** O resultado final é uma tabela com os clientes separados em decis. As informações mais relevantes em cada divisão são: quantidade de clientes envolvida, quantos são bons, quantos são ruins, porcentagem de maus clientes evitada e o lucro que cada seleção de clientes proporciona. 

## 📊 [Análise Exploratória de Dados para Olist](https://github.com/caiocasagrande/olist_eda) 
<sub>[lang:en-US]</sub>

- **A empresa e o problema:** Olist é uma empresa de e-commerce no Brasil que oferece uma ampla gama de produtos em sua plataforma. A empresa reconhece a importância de melhorar sua eficiência operacional e o primeiro passo para isso é entender mais sobre o comportamento de seus consumidores, variações nos pedidos, padrões de vendas por região, diferenças em preços e fretes por estado, satisfação dos clientes e mais. 

- **Objetivo:** Criar uma Análise Exploratória de Dados (EDA) com os dados da empresa cobrindo diferentes áreas do negócio, como pedidos, produtos, consumidores, regiões, a fim de prover informação de qualidade para tomadas de decisão estratégicas.

- **Conclusão:** A análise proprocionou vários *insights* de negócio, como descrição de preços, características de pedidos, tendências temporais, preferências de pagamentos, padrões regionais e diários, relação entre tempo de entrega e avaliação do pedido, etc.
