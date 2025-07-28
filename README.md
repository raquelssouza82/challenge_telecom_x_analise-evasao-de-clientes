# Análise de Churn - Telecom X

## 📌 Visão Geral

Este projeto tem como objetivo analisar os fatores que influenciam a evasão de clientes (churn) na Telecom X, uma empresa de telecomunicações com alta taxa de cancelamento. A análise foi realizada com dados reais utilizando Python e bibliotecas como Pandas, Seaborn e Matplotlib, visando extrair insights para apoiar estratégias de retenção.

---

## 📂 Estrutura do Projeto

- `notebook.ipynb` — Notebook principal com todo o fluxo de análise, desde a limpeza dos dados até a visualização e interpretação dos resultados.
- `data/` — Pasta contendo os arquivos CSV com os dados brutos utilizados na análise.
- `README.md` — Este arquivo, contendo a documentação do projeto.

---

## 🚀 Como Executar
git clone https://github.com/seu-usuario/telecom-x-churn.git


### Pré-requisitos

- Python 3.7 ou superior
- Jupyter Notebook ou Google Colab
- Bibliotecas: pandas, numpy, matplotlib, seaborn


## 🔍 Análise e Insights
A análise cobre:

*Perfil do churn baseado no tempo de permanência (tenure)
*Impacto do tipo de contrato na evasão
*Influência do perfil familiar (parceiro e dependentes)
*Relação entre serviços contratados e churn
*Efeito da forma de pagamento e uso da fatura digital

Principais conclusões e recomendações estão comentadas no notebook e abaixo para fácil entendimento.


# Análise de Churn na Telecom X — Insights e Oportunidades

## Panorama Geral  
Embora a maioria dos clientes mantenha seus contratos ativos, o churn ocorre com maior intensidade em determinados perfis e contextos, apontando áreas críticas para retenção.

## Principais Fatores de Risco Identificados

- **Tempo de contrato:** Clientes recentes (menor tenure) apresentam risco significativamente maior de cancelamento, indicando necessidade de maior atenção logo após a contratação.

- **Tipo de contrato:** Contratos mensais têm churn elevado, enquanto contratos anuais/bienais funcionam como barreiras eficazes contra cancelamento precoce.

- **Contexto familiar:** A presença de parceiro(a) e dependentes está correlacionada a menor churn, sugerindo que compromissos familiares aumentam o valor percebido do serviço.

- **Uso dos serviços:** Clientes que não contratam serviços adicionais (suporte técnico, segurança, proteção de dispositivos) têm maior propensão a churn, mostrando a importância de ofertar pacotes completos.

- **Método de pagamento:** Pagamentos via fatura digital e cheque eletrônico apresentam maior churn, possivelmente devido a perfis mais voláteis ou menor envolvimento.

## Oportunidades para Redução do Churn

- **Estratégias de onboarding:** Criar programas focados no primeiro trimestre de contrato para educar, engajar e antecipar possíveis problemas dos novos clientes.

- **Promoção de planos longos:** Incentivar contratos anuais e bienais com descontos ou benefícios exclusivos para aumentar a permanência.

- **Cross-selling inteligente:** Oferecer de forma personalizada os serviços complementares que agregam valor e dificultam o cancelamento.

- **Campanhas segmentadas por perfil de pagamento:** Adaptar abordagens para clientes que usam fatura digital ou cheque, com comunicação que aumente o comprometimento.

## Considerações Finais  
A análise indica que o combate ao churn deve ser multidimensional, com foco em ações preventivas especialmente nos primeiros meses, além de incentivar maior engajamento via oferta de serviços e contratos mais longos. Dados e segmentações claras são aliados essenciais para a eficácia das estratégias.




