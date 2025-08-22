---
title: Shift-to-the-Left
layout: default
parent: Conceitos
---

# 📘 Shift-to-the-Left

**Shift-to-the-left** é uma abordagem estratégica que visa antecipar atividades críticas no ciclo de desenvolvimento de software — como testes, segurança e validação — para fases mais iniciais do processo. O objetivo é detectar e resolver problemas o mais cedo possível, reduzindo riscos, custos e refactors.

---

## Benefícios

- **Redução de custos**: Corrigir falhas no início é significativamente mais barato.
- **Melhoria da qualidade**: Produtos mais robustos e confiáveis.
- **Agilidade na entrega**: Menos refactors e menos bloqueios durante o desenvolvimento.
- **Colaboração entre áreas**: Equipes de gestão, desenvolvimento e QA atuam de forma integrada desde o início.

---

## Aplicações Práticas

### ❔ Análise de Requisitos
- Perceber o objetivo do produto/funcionalidade
- Discutir diferentes soluções para resolver um problema, permite avaliar atempadamente o impacto do desenvolvimento

### 🧪 Testes 
- Integração de testes automatizados desde as fases iniciais.
- Uso de testes unitários, de integração e validação contínua.
- Ferramentas comuns: Jest, JUnit, Cypress, GitHub Actions.

### 🔐 Segurança 
- Inclusão de práticas de segurança desde o design e codificação.
- Análise estática de código, validação de dependências, modelagem de ameaças.
- Ferramentas comuns: SonarQube, Snyk, OWASP ZAP.

### 📊 Qualidade e Performance
- Monitoramento de desempenho e métricas desde o desenvolvimento.
- Validação de requisitos não funcionais antecipadamente.

---

## Práticas Recomendadas

- **Integração Contínua (CI)**: Automatizar testes e validações a cada commit.
- **Revisões de Código**: Realizadas em pares ou com ferramentas automatizadas.
- **Análise Estática**: Validar padrões de código e segurança antes da compilação.
- **Infraestrutura como Código (IaC)**: Validar configurações e políticas desde o início.

---

## Considerações

A adoção do shift-to-the-left exige mudanças culturais e técnicas. É fundamental que todas as áreas envolvidas no desenvolvimento estejam alinhadas com os objetivos e práticas da abordagem, promovendo uma cultura de qualidade desde o início.
