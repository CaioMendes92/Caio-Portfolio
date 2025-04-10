# Caio Portfólio
## Boas Vindas
Olá, seja bem-vindo(a) ao meu portfólio de projetos de Ciência de Dados.
Nessa página, eu demonstro minhas habilidades de resolver problemas de negócio
utilizando conceitos e ferramentas da Ciência de Dados, através de projetos com dados
públicos.
Você vai encontrar também: Minhas experiências profissionais, habilidades,
ferramentas e conceitos envolvendo a Ciência de Dados.
Sinta-se à vontade para entrar em contato através dos links no final da página.

![alt text](https://github.com/CaioMendes92/Caio-Portfolio/blob/main/Banner.jpg)

## Sobre mim
Data Scientist

Meu nome é Caio Mendes e tenho 32 anos. Sou formado em Física e tenho doutorado na área de computação quântica pela Universidade Federal de Alagoas. 
Atualmente, trabalho na empresa AI Solutions, onde sou Cientista de Dados. Trabalho em diversos projetos diferentes, dentre eles verificar um grande conjunto de dados para encontrar possíveis (ou já realizadas) fraudes dentro dos serviço público. Para isso, desenvolvo pipelines no Apache Airflow, crio consultas em SQL utilizando Python para webscrapping e análise de dados. Utilizo o DBT para realizar limpeza dos dados e criar testes automatizados de forma a assegurar a qualidade dos dados. Crio dashboards para o acompanhamento dos resultados e os apresento para o líder não técnico.

Anteriormente, trabalhei na empresa Mesha Tecnologia, onde fui Analista de Dados. A mesha é uma empresa que terceiriza funcionários, fiquei alocado no SESI do estado de Alagoas e tive como função Conectar diversas fontes de dados, principalmente em ambientes cloud e, utilizando queries em SQL, obter dados e transforma-los em insights de negócio a partir do desenvolvimento de dashboards em Power BI. Gerar relatórios semanais com os principais resultados da empresa, se baseando nos dados e, utilizando de storytelling, passar os resultados para as equipes de outras áreas.
Antes disso, trabalhei como programador em uma empresa de marketing digital.
Trabalhei na criação e organização de banco de dados, sendo utilizado um banco não relacional (MongoDB).
Além disso, fui responsável por geração de insights a partir de dados e criação de dashboards usando Power BI.

Estou buscando sempre me aprimorar e aprender cada vez mais para melhorar a tomada de decisão das empresas por onde passo.

## Habilidades

### Linguagens de Programação e Banco de Dados
- Python e PySpark com foco em análise de dados.
- SQL para extração de dados
- Banco de Dados SQLite, Postres, MySQL, OracleDB e MongoDB.

### Estatística e Machine Learning
- Estatística descritiva
- Algoritmos de Regressão, Classificação, Clusterização
- Técnicas de balanceamento dos dados, seleção de atributos e redução de dimensionalidade

### Métricas de performance dos algoritmos
- RMSE
- MAE
- MAPE
- Confusion Matrix
- AUC/ROC
- Accuracy

### Pacotes de Machine Learning
- Sklearn
- Scipy

### Visualização de Dados
- Matplotlib
- Seaborn
- Plotly
- PowerBI
- Data Studio

### Engenharia
- Airflow
- Docker
- Git
- Github
- Gitlab
- Virtual Environment
- Streamlit
- Flask
- Python API's
- Cloud Heroku

**Links**:
    
[![Linkedin](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/caio-vitor-castro-mendes-6654751ba/)
&nbsp;
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/CaioMendes92);


## Projetos de Data Science:

### Detecção de Fraudes em Transações com Cartão Presencial via ML  (**EM CONSTRUÇÃO**)
Desenvolvimento de uma solução completa de machine learning para detecção de fraudes em transações com cartão de crédito realizadas exclusivamente em terminais físicos. O projeto utiliza um pipeline estruturado com a metodologia CRISP-DM, desde a ingestão e tratamento de dados até a modelagem e avaliação de impacto financeiro.

A etapa de engenharia de features contempla variáveis temporais, comportamentais, espaciais e estatísticas agregadas por janelas de tempo (rolling windows). As variáveis são documentadas e versionadas em um feature store com controle de ciclo de vida. O modelo final — baseado em LightGBM — apresenta desempenho sólido com AUC-ROC de 0.72, F1-score de 0.50, precision acima de 92% e recall próximo de 35%.

Simulações demonstram que, caso implementado, o modelo reduziria os prejuízos por fraude de R$ 411.671,78 para R$ 94.039,41, representando uma economia de 77%.

Próximos passos incluem a construção de testes unitários, deploy do modelo com API, orquestração via Airflow e integração com a nuvem (AWS).

[Fraud Detection](https://github.com/CaioMendes92/fraud_detection)

### Clusterização de clientes de um e-commerce com o intuito de criar um programa de fidelidade com os melhores clientes
Utilizando técnicas de Machine Learning e análise de dados, foi possível dividir
os clientes de um e-commerce em grupos, de forma que se crie um grupo para o
programa de fidelidade e a equipe de Marketing consiga acompanhar e gerar
receitas de formas direcionadas para cada grupo.
Foi utilizado algoritmos como o KMeans, Hierarchical Clustering, Gaussian
Mixture Model e DBSCAN para encontrar os melhores resultados dos clusters.

[Customer Segmentation](https://github.com/CaioMendes92/customer_segmentation)

### Criação de um ranking com clientes com maior propensão de adquirir um seguro saúde.
Utilizando Python, análise de dados e técnicas de classificação, fui capaz de
gerar um ranking, classificando clientes com maior propensão de aceitar um
seguro saúde. O projeto tinha como intuito a redução de custos nas ligações
para possíveis novos clientes.
Foi utilizado algoritmos como XGBoost, AdaBoost, Randon Forest para encontrar
o melhor ranking

[Health Insurance Cross Sell](https://github.com/CaioMendes92/health_insurance_cross_sell)

### Previção de vendas para as próximas seis semanas, usando o algoritmo de regressão XGboost
[Rossmann Store Sales](https://github.com/CaioMendes92/RossmannStoreSales)

Eu usei Python, análise de dados e técnicas de Machine Learning para encontrar
uma solução que prevesse os preços de cada loja nas próximas seis semanas. E o
resultado dessa solução, caso fosse implementada, seria de mais de $ 200MM de
dólares de receita.
Foi utilizado algoritmos como XGBoost, Regressão Linear, Lasso e Random Forest
para encontrar o melhor resultado

## Projetos de Análise de Dados
### Acompanhamento Mensal das Transferências Obrigatórias da União Utilizando BS4 + Airflow
Utilizando o Beatifulsoup, foi realizado a raspagem dos dados referente as
transferências obrigatórias da União no estado de Alagoas no período de 2017
até 2022. Com o intuito de manter os dados atualizados, foi utilizado o Apache
Airflow para orquestrar e baixar mensalmente os dados.

[Transferencias Obrigatorias da Uniao](https://github.com/CaioMendes92/Acompanhamento-Mensal-das-Transfer-ncias-Obrigat-rias-da-Uni-o-utilizando-BS4-Airflow)

### Criação de um dashboard para análise de dados dos alunos que realizaram a prova do ENEM 2020.
Utilizando o Power BI, foi possível construir um Dashboard para acompanhamento
das notas e análises de dados referente aos alunos do ENEM 2020.

[Power BI analysis of ENEM candidates](https://github.com/CaioMendes92/Teste-Analista-de-Dados-MESHA)


