# HumanizaSUS — Diagnóstico de Humanização em Unidades de Saúde

## 📌 Visão geral
Este repositório apresenta um **MVP de análise de dados** voltado ao diagnóstico de humanização em unidades de saúde, com base em questionários aplicados a profissionais da rede.

O foco do projeto é o **produto final**: um relatório analítico que consolida respostas, gera indicadores e apoia a tomada de decisão da gestão pública, em consonância com as diretrizes da Política Nacional de Humanização (HumanizaSUS).

---

## 📄 Produto final
O principal artefato do projeto é o relatório:

**📘 `portifolio_humanizaSUS.pdf`**

Neste documento estão descritos:
- o problema analisado  
- a metodologia adotada  
- o tratamento e padronização dos dados  
- os indicadores construídos  
- as análises e visualizações  
- interpretações e recomendações para a gestão  

👉 Este PDF representa o **resultado entregue ao gestor**.

---

## 📊 Processo analítico
O notebook abaixo documenta o pipeline utilizado para gerar os resultados:

**📓 `index.ipynb`**

Ele contém:
- leitura e consolidação dos arquivos de questionário  
- limpeza e padronização dos dados  
- anonimização das unidades  
- conversão das respostas para escala Likert (1–4)  
- construção de indicadores por área do HumanizaSUS  
- geração das tabelas e gráficos utilizados na análise  

O notebook foi mantido de forma **simples e transparente**, com o objetivo de evidenciar o raciocínio analítico e o fluxo de processamento dos dados.

---

## 🧠 Abordagem metodológica
- Questionário estruturado com respostas qualitativas  
- Conversão para **escala Likert**  
- Agrupamento das perguntas por **áreas de atuação do HumanizaSUS**  
- Cálculo de:
  - médias por área  
  - média geral por unidade  
  - número de respondentes  
  - medidas de dispersão  
- Análise comparativa entre unidades  

O projeto adota uma abordagem **descritiva e diagnóstica**, não preditiva.

---

## 🎯 Objetivo do MVP
Demonstrar a capacidade de:
- transformar dados brutos em indicadores relevantes  
- estruturar uma análise aplicada a políticas públicas  
- entregar um produto analítico compreensível para gestores  
- organizar um projeto de dados de ponta a ponta  

Este MVP foi pensado como base para evoluções futuras, como:
- geração automática de relatórios em PDF  
- uso de IA para interpretação textual dos indicadores  
- interface web para upload de dados e visualização dos resultados  

---

## 🚧 Próximos passos (planejados)
- Automatizar a geração do relatório final  
- Integrar análise textual assistida por IA  
- Desenvolver interface simples para uso por gestores  
- Padronizar o questionário para reaplicações periódicas  

---

## 👤 Autor
**Alan Alves**  
Analista de Dados | Ciência de Dados aplicada a Políticas Públicas  

---

## ℹ️ Observação
Este repositório foi mantido propositalmente **enxuto**, priorizando clareza, funcionalidade e alinhamento com o estágio atual de desenvolvimento do projeto.
