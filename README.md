# Olá, eu sou Kaio Paiva 👋

### Dados que saem do notebook e chegam à decisão

🌐 [Veja meu portfólio completo](https://kaio-data-portfolio.peachymaple21.chatgpt.site)

Gosto de pegar um problema meio solto, entender o que realmente precisa ser respondido e transformar isso em uma solução que outra pessoa consiga usar. Trabalho da ingestão à análise, passando por qualidade, modelagem, machine learning e operação. Nos projetos abaixo eu mostro o código, as decisões que tomei e também o que ainda pode melhorar.

## Projetos em destaque

### [Retail Analytics Platform](https://github.com/10kdts/retail-analytics-platform)

Plataforma analítica para varejo com pipeline ETL, PostgreSQL, modelo dimensional, controles de qualidade e estrutura para consumo no Power BI.

`Python` `SQL` `PostgreSQL` `Data Warehouse` `Power BI` `GitHub Actions`

### [Customer 360 Data Platform](https://github.com/10kdts/customer-360-data-platform)

Arquitetura Bronze/Silver/Gold que integra CRM, pedidos, pagamentos, comportamento e suporte. Inclui resolução de identidade, contratos, deduplicação, quarentena, dbt, Airflow, Redpanda, MinIO e governança LGPD.

**Evidência de execução:** 3.566 registros Bronze, 2.509 Silver, 99 clientes Gold, seis registros em quarentena e cinco eventos duplicados removidos.

`Python` `SQL` `dbt` `Airflow` `Redpanda` `MinIO` `Docker` `Data Governance`

### [Fraud Detection MLOps](https://github.com/10kdts/fraud-detection-mlops)

Sistema explicável de detecção de fraude com divisão temporal, prevenção de leakage, regressão logística ponderada, limiar orientado a custo, API de scoring, hash do modelo, PSI e runbook de rollback.

**Evidência de teste:** Average Precision 0,144 e recall de 60% em dados sintéticos desbalanceados; as limitações estão registradas no model card.

`Machine Learning` `MLOps` `API` `Model Monitoring` `Docker` `CI/CD`

### [Pipeline financeiro em tempo quase real](https://github.com/10kdts/realtime-financial-pipeline)

Eu montei este pipeline para lidar com o que acontece quando uma transação chega repetida, atrasada ou fora de ordem. Ele usa tempo do evento, watermark, janela por conta, quarentena e replay idempotente, com contrato de dados, runbook e CI.

**Evidência de execução:** 1.204 mensagens, 1.201 eventos únicos, três duplicidades, um evento atrasado recuperado e 53 alertas.

`Python` `Event Streaming` `Redpanda` `SQLite` `Docker` `GitHub Actions`

## Competências

| Área | Ferramentas e práticas |
|---|---|
| Engenharia de dados | Python, SQL, ETL/ELT, modelagem dimensional, batch e eventos |
| Plataforma | PostgreSQL, MinIO, Redpanda/Kafka, Docker, Airflow e dbt |
| Qualidade e governança | Contratos, testes, lineage, observabilidade, LGPD e runbooks |
| Analytics | KPIs, Customer 360, Power BI e comunicação de resultados |
| Machine Learning | Classificação, desbalanceamento, validação temporal, custo e drift |
| Engenharia de software | Git, testes automatizados, CI/CD, APIs e documentação arquitetural |

## Meu jeito de trabalhar

- Antes de escolher a ferramenta, tento deixar claro qual decisão o dado precisa apoiar.
- Não considero um pipeline pronto se reprocessamento, qualidade e falhas ficaram para depois.
- Registro as limitações do que construí, principalmente quando trabalho com dados sintéticos.
- Deixo comandos, testes e CI para que o projeto possa ser executado sem depender de mim.

## Em construção

- Forecast de vendas com backtesting
- Projeto cloud com infraestrutura como código

## Contato

Se algum projeto fizer sentido para o problema que você está tentando resolver, pode falar comigo pelo GitHub. Gosto de trocar ideia sobre dados, produto e decisões de arquitetura.

