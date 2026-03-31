# MonitoramentoDevOps_SRE

# 🚀 New Relic Observability Lab: Hands-on Interface & NRQL

Este repositório documenta meu aprendizado prático na plataforma de observabilidade **New Relic**. O foco deste laboratório foi explorar as capacidades da ferramenta diretamente pelo painel (SaaS), sem a necessidade inicial de agentes locais, focando em extração de dados e criação de visualizações.

## 🎯 Objetivos do Lab
* Explorar a interface de **Integrations & Agents** (APM, Infrastructure, Kubernetes).
* Dominar a sintaxe básica da linguagem **NRQL** (New Relic Query Language).
* Realizar o ciclo completo de monitoramento: **Consulta -> Análise -> Dashboards**.

## 🛠️ Tecnologias e Ferramentas
* **Plataforma:** New Relic (Paid/Sandbox Tier)
* **Linguagem:** NRQL
* **Formato de Saída:** JSON e Visualizações Gráficas (Billboard)

## 📋 Atividades Realizadas

### 1. Exploração de Dados (Query Builder)
Utilizei o motor de consultas do New Relic para validar a ingestão de dados e metadados da conta. 
* **Query de Teste:** ```sql
  SELECT count(*) FROM NrUsage SINCE 24 HOURS AGO
