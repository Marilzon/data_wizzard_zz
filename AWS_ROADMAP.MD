# Curso AWS para Engenharia de Dados

## 1. Fundamentos Avançados de Python no AWS
**Objetivo**: Dominar conceitos avançados de Python com foco em desenvolvimento na AWS.  
**Conteúdos**:
- Tipagem dinâmica e forte no desenvolvimento AWS Lambda.
- Funções anônimas (lambda) e funções de alta ordem em serviços AWS.
- Decorators e context managers em funções Lambda e automações.
- Integração de Python com AWS SDK (boto3).  
**Aplicações**:
- Criar funções Lambda reutilizáveis para manipulação de dados.
- Implementar bibliotecas customizadas para transformação de dados em AWS Lambda.

## 2. Manipulação e Transformação de Dados com AWS
**Objetivo**: Manipular grandes volumes de dados de forma eficiente na AWS.  
**Conteúdos**:
- Amazon S3 e Amazon Athena para manipulação de grandes datasets.
- Pandas e NumPy em instâncias EC2 e Lambda.
- Operações vetorizadas usando instâncias otimizadas para Machine Learning (SageMaker).
- Integração com AWS Glue para ETL em grande escala.  
**Aplicações**:
- Criar um pipeline ETL usando AWS Glue e S3 para processar grandes volumes de dados.
- Normalizar datasets armazenados no S3 e gerar relatórios via Athena.

## 3. Data Pipelines e Integração de Dados na AWS
**Objetivo**: Automatizar o fluxo de dados em arquiteturas de big data na AWS.  
**Conteúdos**:
- AWS Glue e Step Functions para automação de ETL.
- Integrações via AWS SDK (boto3), APIs e serviços de streaming (Kinesis).
- Conectores para bancos de dados (RDS, Aurora) e data lakes (S3).
- Uso de EMR e Spark para pipelines distribuídos.  
**Aplicações**:
- Criar pipelines de dados escaláveis com Glue, Step Functions e PySpark no EMR.
- Implementar integração contínua de APIs externas e armazenamento no S3.

## 4. Desenvolvimento de APIs e Serviços de Dados na AWS
**Objetivo**: Construir serviços de dados eficientes e seguros na AWS.  
**Conteúdos**:
- API Gateway para criar APIs.
- AWS Lambda com FastAPI/Flask para construir serviços sem servidor.
- Integração com DynamoDB e RDS.
- Implementação de segurança com IAM e autenticação.  
**Aplicações**:
- Criar uma API para consultar dados no RDS e processar agregações em tempo real.
- Implementar uma API de ingestão de dados que salva diretamente em DynamoDB ou S3.

## 5. Engenharia de Dados em Tempo Real na AWS
**Objetivo**: Implementar soluções de ingestão e processamento de dados em tempo real na AWS.  
**Conteúdos**:
- Amazon Kinesis e Amazon MSK (Kafka gerenciado) para streaming.
- Integração com AWS Lambda e Kinesis Firehose.
- Processamento em tempo real com Amazon EMR e Spark Streaming.  
**Aplicações**:
- Criar um pipeline de ingestão de dados em tempo real usando Kinesis e Lambda.
- Implementar um dashboard de métricas agregadas usando QuickSight para dados de streaming.

## 6. Otimização e Performance em Pipelines na AWS
**Objetivo**: Maximizar a eficiência dos pipelines e o uso dos serviços AWS.  
**Conteúdos**:
- Ferramentas de profiling em Python no EC2 e Lambda.
- Gerenciamento de custos com AWS Cost Explorer e otimização de recursos.
- Uso de serviços otimizados como AWS Lambda para processamento sob demanda.
- Multithreading e asyncio em ambientes distribuídos na AWS.  
**Aplicações**:
- Identificar e otimizar gargalos em pipelines de ETL usando Glue e Lambda.
- Reescrever rotinas críticas com otimizações específicas para AWS.

## 7. Testes e Qualidade de Código na AWS
**Objetivo**: Garantir robustez e sustentabilidade em aplicações na AWS.  
**Conteúdos**:
- Testes unitários e de integração com pytest em funções Lambda.
- Ferramentas de CI/CD da AWS (CodePipeline, CodeBuild).
- Linters (flake8, black) e integração com CodeCommit.  
**Aplicações**:
- Configurar testes automatizados em pipelines AWS.
- Implementar pipelines de CI/CD que validam alterações antes de implantar em produção.

## 8. Data Warehousing e Arquitetura de Dados na AWS
**Objetivo**: Estruturar soluções de armazenamento e integração de dados escaláveis na AWS.  
**Conteúdos**:
- Amazon Redshift e modelagem de dados para data warehouses.
- Integração com Amazon S3 e Glue para data lakes.
- Armazenamento distribuído com Redshift Spectrum e Athena.
- Implementação de arquitetura Medallion no AWS (bronze, silver, gold).  
**Aplicações**:
- Criar um data warehouse no Redshift e integrar com S3 para consultas rápidas.
- Implementar camadas de dados em S3 com Glue Catalog e Athena.
