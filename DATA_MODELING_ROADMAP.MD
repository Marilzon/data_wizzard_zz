# Curso de Modelagem de Dados para Engenharia de Dados

## 1. Fundamentos da Modelagem de Dados
**Objetivo**: Entender os princípios fundamentais da modelagem de dados e sua aplicação em projetos de engenharia de dados.  
**Conteúdos**:
- Tipos de modelagem: conceitual, lógica e física.
- Entidades, atributos, chaves primárias e estrangeiras.
- Relacionamentos entre entidades (1:1, 1:N, N:N).
- Normalização (1FN, 2FN, 3FN) e desnormalização.  
**Aplicações**:
- Modelar o esquema de um banco de dados relacional para um sistema de CRM.
- Normalizar um modelo de dados para otimizar consultas e integridade.

## 2. Modelagem Relacional de Dados
**Objetivo**: Criar modelos relacionais eficientes para suportar grandes volumes de dados.  
**Conteúdos**:
- Modelagem de dados relacionais: tabelas, colunas e relações.
- Diagramas Entidade-Relacionamento (ERD).
- Tabelas de associação e junções complexas.
- Análise de cardinalidade e dependências funcionais.  
**Aplicações**:
- Projetar um banco de dados relacional para uma plataforma de e-commerce.
- Otimizar modelos relacionais para reduzir a redundância de dados e melhorar a eficiência.

## 3. Modelagem Dimensional e Data Warehousing
**Objetivo**: Desenvolver modelos dimensionais para data warehouses e análises OLAP.  
**Conteúdos**:
- Diferenças entre OLTP e OLAP.
- Modelagem dimensional: tabelas fato e dimensões.
- Star schema e Snowflake schema.
- Slowly Changing Dimensions (SCDs).  
**Aplicações**:
- Projetar um modelo dimensional para um data warehouse de uma empresa de vendas.
- Implementar um Star Schema para otimizar relatórios analíticos.

## 4. Modelagem de Dados NoSQL
**Objetivo**: Criar modelos de dados eficientes para bancos NoSQL, como Cassandra, MongoDB e DynamoDB.  
**Conteúdos**:
- Diferenças entre bancos de dados relacionais e NoSQL.
- Modelagem de dados em chave-valor, documentos, grafos e colunas.
- Denormalização e trade-offs em ambientes NoSQL.
- Modelagem para consistência e escalabilidade.  
**Aplicações**:
- Projetar um esquema para uma aplicação de redes sociais usando um banco de dados NoSQL.
- Modelar dados em MongoDB para armazenar grandes volumes de dados de eventos de usuários.

## 5. Modelagem para Data Lakes e Big Data
**Objetivo**: Entender os desafios de modelagem em arquiteturas de Big Data e Data Lakes.  
**Conteúdos**:
- Diferenças entre data lakes e data warehouses.
- Modelagem de dados em camadas: bronze, silver e gold (Medallion Architecture).
- Armazenamento e versionamento de dados com Delta Lake.
- Governança e catalogação de dados (AWS Glue, Apache Hive).  
**Aplicações**:
- Criar um modelo de dados em camadas para um data lake utilizando a arquitetura Medallion.
- Modelar uma estrutura de armazenamento distribuído para um projeto de big data com petabytes de dados.

## 6. Modelagem para Performance e Escalabilidade
**Objetivo**: Aprender técnicas de modelagem de dados que otimizam a performance em ambientes com grandes volumes de dados.  
**Conteúdos**:
- Particionamento e sharding de dados.
- Modelagem para indexação eficiente.
- Estratégias de caching e pré-agregação.
- Modelagem para consultas complexas e alta concorrência.  
**Aplicações**:
- Projetar um banco de dados escalável para uma aplicação de IoT que processa milhões de eventos por segundo.
- Implementar uma estratégia de particionamento para otimizar a performance de consultas em um data warehouse.

## 7. Ferramentas e Práticas de Modelagem de Dados
**Objetivo**: Utilizar ferramentas e boas práticas para modelagem de dados em diferentes ambientes.  
**Conteúdos**:
- Ferramentas de modelagem: ER/Studio, MySQL Workbench, DBDesigner.
- Documentação e versionamento de modelos de dados.
- Revisão e otimização de modelos.
- Práticas de governança de dados e conformidade.  
**Aplicações**:
- Utilizar ER/Studio para criar e documentar modelos de dados de uma organização.
- Implementar uma prática de governança de modelos de dados para garantir a integridade e a conformidade.

## 8. Modelagem de Dados para Machine Learning
**Objetivo**: Estruturar dados de maneira eficiente para suportar modelos de Machine Learning.  
**Conteúdos**:
- Estruturação de dados para features e labels.
- Normalização e padronização de dados para ML.
- Feature engineering e criação de pipelines de dados.
- Modelagem de dados em sistemas distribuídos (HDFS, Spark).  
**Aplicações**:
- Projetar um pipeline de dados para preparar dados de treinamento de um modelo de machine learning.
- Implementar uma arquitetura de dados para streaming de features em tempo real.
