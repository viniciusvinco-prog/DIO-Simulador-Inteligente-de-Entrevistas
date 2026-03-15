# Jornada para Analista de Dados / BI (Business Intelligence) — Plano Personalizado

Este repositório documenta uma jornada estruturada para transição/crescimento na carreira de **Analista de Dados / BI (Business Intelligence)**, com foco em **Power BI**, partindo do zero e estudando **7 horas por semana**.

---
## 1. Entrevista Inicial (Perguntas e Respostas)

**Pergunta 1:**  
> "O que mais te atrai em tecnologia - resolver problemas, criar produtos ou entender sistemas?"  
**Resposta:** Ambos.

**Pergunta 2:**  
> "E você já tem experiência na área de tecnologia ou está começando do zero?"  
**Resposta:** Estou começando do zero.

**Pergunta 3:**  
> "Quantas horas por semana você consegue dedicar aos estudos?"  
**Resposta:** 7h/semana.

**Pergunta 4:**  
> "No seu dia a dia, você prefere lidar mais com pessoas, dados ou código?"  
**Resposta:** Dados ou códigos.

**Pergunta 5:**  
> "Qual é seu objetivo principal: conseguir o primeiro emprego, fazer transição de carreira ou crescer na função atual?"  
**Resposta:** Possível transição de carreira ou crescimento na empresa atual. Sou Gerente de Carteira PJ em uma agência de um banco público federal.

**Pergunta 6:**  
> "Quais assuntos ou tecnologias mais despertam seu interesse? Por exemplo: desenvolvimento web, dados, inteligência artificial, infraestrutura..."  
**Resposta:** Dados e inteligência artificial.

**Pergunta 7:**  
> "Você tem alguma experiência prévia (mesmo que não seja em tech) que gostaria de aproveitar nessa nova jornada?"  
**Resposta:**  
- Em tecnologia: experiência amadora com formatação de computadores e reinstalação de sistema operacional e programas.  
- Profissional: Gerente de Carteira PJ (produtos, serviços e crédito), uso de tecnologia nas atividades do trabalho.

---

## 2. Sugestões de Carreira (Ranking) e Escolha

Com base no perfil levantado na entrevista, foram ranqueadas 3 carreiras:

1) **🥇 Analista de Dados / BI (Business Intelligence)** — **Escolhida**  
2) **🥈 Engenheiro de Dados (Data Engineer)**  
3) **🥉 Cientista de Dados / IA aplicada (Data Scientist)**  

**Carreira escolhida:** **Analista de Dados / BI (Business Intelligence)**

---

## 3. Plano de Estudos Personalizado (7h/semana)

### 3.1 Rotina semanal (7h)
Modelo recomendado (ajustável):
- **3h**: Conteúdo guiado (Microsoft Learn / documentação)
- **3h**: Prática no Power BI (hands-on)
- **1h**: Revisão + entrega (documentar aprendizados, melhorar dashboard, organizar portfólio)

> A estrutura do plano segue as competências esperadas para a função de Power BI Data Analyst: **preparar dados, modelar dados, visualizar/analisar e gerenciar/segurança**, com domínio de **Power Query** e **DAX**. [2](https://www.youtube.com/watch?v=7cUrsltJbEI)[4](https://faculdade.grancursosonline.com.br/blog/analista-de-bi/)[5](https://api.asm.skype.com/v1/objects/0-wus-d11-a40578cdffb2fdda9708a2e6a03fa0bb/views/original)

---

### 3.2 Fase 0 — Preparação
**Objetivo:** preparar ambiente e definir um “projeto-guia” alinhado ao contexto bancário/PJ.

**Ações:**
1. Instalar e abrir **Power BI Desktop**; entender o fluxo: obter dados → transformar → modelar → visualizar → publicar.   
2. Definir um tema de projeto ligado ao trabalho (ex.: carteira PJ, funil comercial, crédito, inadimplência, produtos/serviços).

**Entregável:** estrutura de pastas `data/`, `reports/`, `notes/` e primeiro arquivo `.pbix`.

---

### 3.3 Fase 1 — Fundamentos Power BI (Semanas 1–2)
**Objetivo:** conhecer os blocos do Power BI e criar seus primeiros relatórios com dados de amostra.

**Conteúdo (oficial):**
- Treinamento do Power BI no Microsoft Learn (módulos iniciais).   
- Fundamentos do Power BI (entrada e navegação).   

**Pratica:**
- Usar **amostras oficiais** (PBIX/XLSX) para aprender rapidamente observando modelos prontos. A Microsoft reúne amostras e explica como abrir e reutilizar. [6](https://datascienceenthusiasts.com.br/guia-carreiras-salarios-dados-brasil-2025/)  

**Entregável:** 1 relatório simples com **2–3 páginas** (ex.: visão geral + detalhamento).

---

### 3.4 Fase 2 — Power Query (ETL) (Semanas 3–4)
**Objetivo:** dominar importação, limpeza, tratamento de erros e padronização de dados.

**Conteúdo:**
- Documentação do **Power Query** (obter/transformar dados, conceitos e boas práticas). [4](https://faculdade.grancursosonline.com.br/blog/analista-de-bi/)  

**Prática:** 1. Construir pipeline com 2 fontes comuns (ex.: Excel/CSV + outra fonte exportada).
2. Padronizar colunas, tipos, chaves, remover duplicados e tratar nulos.

**Entregável:** Dataset “limpo” pronto para modelagem (etapas documentadas no Power Query).

---

### 3.5 Fase 3 — Modelagem de Dados (Semanas 5–6)
**Objetivo:** construir um modelo semântico bem estruturado (fato/dimensões e relacionamentos corretos).

**Referência (orientação oficial da função/PL-300):**
- A certificação/role do Power BI Data Analyst cobre **modelagem** como competência central. [2](https://www.youtube.com/watch?v=7cUrsltJbEI)[3](https://www.udemy.com/course/power-bi-power-bi-completo-do-basico-ao-avancado/)  

**Prática:** Organizar o modelo em:
  - 1 tabela fato (ex.: operações, propostas, vendas)
  - Dimensões (tempo, agência, produto, cliente/segmento, canal etc.)
- Validar filtros/segmentações e relacionamento (cardinalidade, direção).

**Entregável:** 1 página do relatório funcionando com filtros consistentes e sem ambiguidade.

---

### 3.6 Fase 4 — DAX (Medidas e Tempo) (Semanas 7–9)
**Objetivo:** criar KPIs reais com medidas, contexto de filtro e comparações por período.

**Conteúdo:**
- Referência de DAX no Microsoft Learn. [5](https://api.asm.skype.com/v1/objects/0-wus-d11-a40578cdffb2fdda9708a2e6a03fa0bb/views/original)  
- Visão geral do DAX (medidascia (orientação oficial da função/PL-300):**
- O perfil do Data Analyst deve entregar insights acionáveis com visualizações compreensíveis. [2](https://www.youtube.com/watch?v=7cUrsltJbEI)[3](https://www.udemy.com/course/power-bi-power-bi-completo-do-basico-ao-avancado/)  

**Prática:** Criar 2 páginas:
  1) **Executiva**: KPIs + tendência + alertas
  2) **Diagnóstico**: decomposição por produto, segmento, agência, canal, período

**Entregável:** Relatório com narrativa clara, layout consistente e filtros bem posicionados.

---

### 3.8 Fase 6 — Power BI Service & Governança (Semanas 12–13)
**Objetivo:** publicar, compartilhar, entender workspaces e fundamentos de segurança.

**Conteúdo:**
- A função/PL-300 inclui **gerenciar e proteger** conteúdo no Power BI. [2](https://www.youtube.com/watch?v=7cUrsltJbEI)[3](https://www.udemy.com/course/power-bi-power-bi-completo-do-basico-ao-avancado/)  
- Laboratórios oficiais PL-300 (hands-on) para praticar cenários reais (workspaces, dashboards, segurança). [7](https://bing.com/search?q=Power+Query+documenta%c3%a7%c3%a3o+Microsoft+Learn)[8](https://learn.microsoft.com/en-us/power-query/)  

**Prática:** 1. Publicar relatório (quando possível).
2. Criar estrutura de workspace (se aplicável) e documentar atualização/refresh.
3. Estudar noções de controle de acesso e RLS (conceitualmente e via labs). [8](https://learn.microsoft.com/en-us/power-query/)[7](https://bing.com/search?q=Power+Query+documenta%c3%a7%c3%a3o+Microsoft+Learn)  

**Entregável:** 1. Relatório “publicável” + documentação simples (`README` do relatório: objetivo, KPIs, origem dos dados, atualização).

---

### 3.9 Fase 7 — Portfólio Direcionado (Banco/PJ) (Semanas 14–16)
**Objetivo:** consolidar portfólio com 2 projetos completos (sem dados sensíveis; usar dados fictícios/anonimizados/amostras).

**Projeto 1 (Carteira PJ / Comercial):**
- KPIs: base, ativação, cross-sell, funil, performance por segmento/canal.

**Projeto 2 (Crédito / Risco operacional básico):**
- KPIs: concessão, atraso, inadimplência, coortes, concentração por perfil/segmento.

> Para praticar com dados de amostra, a Microsoft oferece datasets e PBIX prontos (e explica formatos). [6](https://datascienceenthusiasts.com.br/guia-carreiras-salarios-dados-brasil-2025/)[11](https://www.linkedin.com/pulse/mercado-de-dados-out-2025-jo%C3%A3o-salom%C3%A3o-yfxpc/)  

**Entregáveis (para cada projeto):**
- `.pbix` final
- 2 páginas (executiva + diagnóstico)
- 10–20 medidas DAX
- arquivo `docs/metricas.md` explicando KPIs e definições
- 1 resumo: “pergunta de negócio → análise → insight → recomendação”

---

## 4. Checklist de Prontidão (Empregável / Movimentação Interna)

Você estará pronto para atuar como BI (nível júnior/interno) quando conseguir:
- Preparar dados com Power Query (limpar, transformar, tratar erros). [4](https://faculdade.grancursosonline.com.br/blog/analista-de-bi/)  
- Modelar dados com relacionamentos e estrutura fato/dimensão. [2](https://www.youtube.com/watch?v=7cUrsltJbEI)[3](https://www.udemy.com/course/power-bi-power-bi-completo-do-basico-ao-avancado/)  
- Criar medidas DAX com contexto de filtros e comparações de tempo. [9](https://dados.gov.br/)[5](https://api.asm.skype.com/v1/objects/0-wus-d11-a40578cdffb2fdda9708a2e6a03fa0bb/views/original)  
- Construir relatórios claros com narrativa (executivo + diagnóstico). [2](https://www.youtube.com/watch?v=7cUrsltJbEI)  
- Publicar/organizar no Service com noções de governança e segurança (básico). [8](https://learn.microsoft.com/en-us/power-query/)[2](https://www.youtube.com/watch?v=7cUrsltJbEI)  

---

## 5. Recursos Oficiais e Referências

### Microsoft Learn / Documentação (Recomendado)
- Treinamento do Power BI (Microsoft Learn): https://learn.microsoft.com/pt-br/training/powerplatform/power-bi   
- Fundamentos do Power BI: https://learn.microsoft.com/pt-br/power-bi/fundamentals/   
- Documentação do Power Query: https://learn.microsoft.com/pt-br/power-query/ [4](https://faculdade.grancursosonline.com.br/blog/analista-de-bi/)  
- Referência de DAX: https://learn.microsoft.com/pt-br/dax/ [5](https://api.asm.skype.com/v1/objects/0-wus-d11-a40578cdffb2fdda9708a2e6a03fa0bb/views/original)  
- Guia de estudo PL-300 (pt-BR): https://learn.microsoft.com/pt-br/credentials/certifications/resources/study-guides/pl-300 [3](https://www.udemy.com/course/power-bi-power-bi-completo-do-basico-ao-avancado/)  
- Certificação Power BI Data Analyst Associate: https://learn.microsoft.com/en-us/credentials/certifications/data-analyst-associate/ [2](https://www.youtube.com/watch?v=7cUrsltJbEI)  

### Labs oficiais (prática real)
- Repositório PL-300 Labs (GitHub): https://github.com/MicrosoftLearning/PL-300-Microsoft-Power-BI-Data-Analyst [7](https://bing.com/search?q=Power+Query+documenta%c3%a7%c3%a3o+Microsoft+Learn)  
- Instruções online dos Labs: https://microsoftlearning.github.io/PL-300-Microsoft-Power-BI-Data-Analyst/ [8](https://learn.microsoft.com/en-us/power-query/)  

### Datasets / Amostras oficiais
- O que são Power BI Samples: https://learn.microsoft.com/en-us/power-bi/create-reports/sample-datasets [6](https://datascienceenthusiasts.com.br/guia-carreiras-salarios-dados-brasil-2025/)  
- Financial Sample (Excel) para prática: https://learn.microsoft.com/en-us/power-bi/create-reports/sample-financial-download [11](https://www.linkedin.com/pulse/mercado-de-dados-out-2025-jo%C3%A3o-salom%C3%A3o-yfxpc/)  
---
