# Portfólio de Projetos em Análise de Dados

**Autor:** Jesus David
**Ambiente:** AntiX Linux / Python 3.13  
**Data:** Abril 2026

## 📌 Sobre o Portfólio

Este portfólio contém **2 projetos completos** de análise de dados aplicados a problemas reais de negócio: 
1. Análise de Churn (Cancelamento de Clientes) - Setor SaaS 
2. Otimização de Campanhas de Marketing - Setor E-commerce

## 🛠️ Tecnologias Utilizadas

Python 3.13, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Jupyter Lab

## 📁 Estrutura do Projeto

portfolio-dados/
├── README.md
├── case1-churn/
│ ├── dados/
│ │ └── (dados gerados via código)
│ └── notebooks/
│ └── case1_churn.ipynb
└── case2-marketing/
├── dados/
│ └── (dados gerados via código)
└── notebooks/
└── case2_marketing.ipynb

## 📊 Case 1: Análise de Churn (Cancelamento de Clientes)

**Contexto do Negócio:** Empresa de software por assinatura (SaaS) com taxa de cancelamento mensal elevada. **Objetivo:** Identificar perfis de risco e criar modelo preditivo para antecipar cancelamentos.

**Abordagem Técnica:** Geração de dataset sintético com 2.000 clientes, análise comparativa entre grupos, modelo Random Forest com 100 árvores, avaliação por acurácia.

**Principais Descobertas:** Clientes que cancelaram têm metade do tempo de relacionamento (18 vs 36 meses), dobram os tickets de suporte (4 vs 2) e usam metade das horas (12 vs 25).

**Resultados do Modelo:** Acurácia de ~80%. Variáveis mais importantes: horas de uso, tickets de suporte, meses como cliente.

**Recomendações:** Criar programa de onboarding para novos clientes, alertar CS quando horas < 10h/mês, priorizar clientes com 3+ tickets em 30 dias.

## 📈 Case 2: Otimização de Campanhas de Marketing

**Contexto do Negócio:** E-commerce com ROI negativo em campanhas de marketing digital. **Objetivo:** Identificar canais e produtos com melhor performance e realocar orçamento.

**Abordagem Técnica:** Dataset com 500 campanhas, métricas CTR/ROAS/lucro/margem, análise por canal/produto, clusterização K-Means.

**Performance por Canal (ROAS médio):** Email (4.5), Instagram (3.2), Google Ads (2.8), TikTok (2.1), Facebook Ads (1.6)

**Classificação dos Produtos:** Estrelas (Acessório, Bolsa) - alto ROAS e alta margem; Vaca Leiteira (Camiseta, Calça) - estáveis; Abacaxi (Tênis) - baixo desempenho.

**Recomendações:** Realocar 70% do orçamento de campanhas com ROAS < 1.5, aumentar investimento em produtos "Estrelas", pausar canais com ROAS < 1.5.

**Impacto Projetado:** Investimento realocado de R$ ~12.000, receita adicional de R$ ~48.000, aumento do ROAS geral em +35%.

## 🚀 Como Executar os Projetos

**Ativar ambiente:** source ~/portfolio-dados/venv/bin/activate

**Iniciar Jupyter:** jupyter lab

**Abrir notebooks:** case1-churn/notebooks/case1_churn.ipynb e case2-marketing/notebooks/case2_marketing.ipynb

**Executar:** Kernel → Restart & Run All

## 📚 Habilidades Demonstradas

Análise Exploratória de Dados, Visualização com matplotlib/seaborn, Machine Learning (Random Forest), Clusterização (K-Means), Storytelling com Dados, Métricas de Negócio (ROAS, Churn, Margem, ROI)

## 🔮 Próximos Passos

Substituir dados sintéticos por dados reais, criar dashboard no Looker Studio, adicionar série temporal, implementar validação cruzada, versionar no GitHub.

## 📞 Contato

**Nome:** Jesus David | **Sistema:** AntiX Linux | **Data:** Abril 2026

*"Transformando dados em decisões de negócio"*
