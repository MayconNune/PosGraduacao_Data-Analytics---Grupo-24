
# 📊 Análise de KPIs - E-commerce Olist

## 📌 Sobre o Projeto

Este projeto foi desenvolvido durante a Pós-Graduação em Data Analytics (FIAP), como parte do Tech Challenge da Fase 1. O objetivo foi analisar o **Brazilian E-Commerce Public Dataset by Olist**, transformando aproximadamente 100 mil pedidos reais em um relatório executivo orientado à tomada de decisão para investidores e acionistas.

A análise foi estruturada em torno de quatro pilares principais:

* 📈 Crescimento e Receita
* 🚚 Logística e SLA
* ⭐ Satisfação do Cliente
* 🔄 Retenção de Clientes

---

## 🎯 Problema de Negócio

Como a Olist pode transformar dados transacionais em insights estratégicos que orientem decisões de investimento, identificando oportunidades de crescimento, gargalos operacionais e riscos à retenção de clientes?

---

## 📊 KPIs Analisados

### 💰 Crescimento e Receita

* Evolução mensal de receita e CMGR (Taxa Composta de Crescimento Mensal)
* Ticket Médio
* Top 10 Categorias por Receita
* Distribuição Geográfica da Receita por Estado

### 🚚 Logística e SLA

* Tempo médio por etapa (Compra → Aprovação → Postagem → Entrega)
* Taxa de Atraso (% de pedidos fora do prazo)
* Desempenho logístico por região/UF

#### 🔍 Estratégias propostas

* Renegociação de SLA com transportadoras nas rotas críticas
* Otimização logística regionalizada
* Calibração de prazos prometidos por região

### ⭐ Satisfação do Cliente

* Correlação entre atraso na entrega e Review Score
* Índice de Aprovação (% CSAT)
* Nota Média de Satisfação ao longo do tempo
* Impacto do atraso na taxa de recompra

#### 🎯 Objetivos

* Medir a percepção geral do cliente
* Avaliar o impacto da logística na satisfação
* Monitorar a evolução da qualidade do serviço

### 🔄 Retenção de Clientes

* Análise de recência e risco de churn
* Taxa de Recompra (clientes novos vs. fiéis)
* Fatores associados à fidelização por categoria

#### 🔍 Análise proposta

* Identificar fatores que levam à não recompra
* Avaliar o impacto de atrasos logísticos na retenção
* Comparar comportamento de clientes recorrentes vs. inativos

#### 🚀 Recomendações iniciais

* Implementar programa de fidelidade para converter a segunda compra
* Desenvolver campanhas de reengajamento segmentadas por recência
* Executar campanha de win-back para clientes inativos há mais de 10 meses
* Priorizar excelência logística como diferencial competitivo no longo prazo

---

## 🛠️ Tecnologias Utilizadas

* Python (Pandas, NumPy, Matplotlib, Seaborn, Plotly)
* Google Colab
* Git e GitHub

---

## 📂 Estrutura do Projeto

```
📁 1 - Projeto-Olist-KPIs
│
├── 📁 Dataset       # Bases de dados originais utilizadas no projeto
├── 📁 Notebook      # Notebooks de análise, tratamento e construção dos KPIs
├── 📁 Scratch       # Scripts auxiliares e experimentais de apoio ao desenvolvimento
├── 📁 docs          # Relatório executivo e documentação do projeto
└── README.md
```

---

## 📈 Objetivo da Análise

* Identificar categorias e regiões mais lucrativas
* Avaliar a eficiência logística ao longo do tempo
* Medir o impacto da logística na satisfação do cliente
* Compreender os fatores que influenciam retenção e recompra
* Gerar recomendações estratégicas orientadas a dados

---

## 🚀 Resultados Esperados

* Insights acionáveis para tomada de decisão
* Identificação de gargalos operacionais
* Recomendações para melhoria da experiência do cliente
* Estratégias para aumento de retenção e receita

---

## 🔗 Links Importantes

* 📓 Notebooks: disponíveis na pasta `Notebook`
* 📁 Dataset: disponível na pasta `Dataset`
* 📄 Relatório Executivo: disponível na pasta `docs`

---

## 👥 Equipe

Projeto desenvolvido em grupo (Grupo 24), com KPIs construídos de forma colaborativa entre os integrantes, cobrindo as quatro dimensões de análise: Crescimento e Receita, Logística e SLA, Satisfação do Cliente e Retenção de Clientes.

---

## 📌 Considerações Finais

Este projeto foi desenvolvido com foco na aplicação prática de análise de dados em um cenário real de e-commerce, integrando diferentes áreas do negócio para gerar valor estratégico por meio de dados.
