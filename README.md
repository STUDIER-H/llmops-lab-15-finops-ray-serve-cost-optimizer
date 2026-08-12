# 🧪 LAB 15: Otimização de Custos (FinOps) & Cluster Distribuído com Ray Serve

## 🎯 Objetivo do Lab
Implementar orquestração distribuída de modelos de ML com Ray Serve e construir a modelagem financeira FinOps para cálculo de custo por token.

---

## 📋 Pré-requisitos
- Ter concluído *Distributed ML Orchestration & FinOps Inference Cost Modeling* (Anyscale / Coursera).
- Ray 2.10+, Ray Serve, Python 3.10+.

---

## 🛠️ O que você deve construir neste Lab:

### Etapa 1: Deployment Distribuído com Ray Serve
1. Escreva uma aplicação Ray Serve (`serve_app.py`) configurando réplicas autoscaláveis entre nós GPU.

### Etapa 2: Modelagem FinOps
1. Desenvolva um módulo `finops/cost_tracker.py` que monitore e calcule em tempo real o custo financeiro exato de cada 1 milhão de tokens gerados com base na tarifa da hora-GPU da AWS.

---

## ✅ Critérios de Aceitação & Entrega
- [ ] Cluster Ray Serve autoscalando com réplicas distribuídas.
- [ ] Relatório de custos FinOps gerado com precisão em dólar por token.
