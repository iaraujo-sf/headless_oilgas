# Headless Oil & Gas — Salesforce Downstream

Repositório de conteúdo sobre o modelo de trabalho **Headless da Salesforce** aplicado ao pilar de **Downstream** no setor de Oil & Gas.

## Objetivo

Construir apresentações, vídeos e materiais que demonstrem como uma empresa de Oil & Gas pode usar o Salesforce como plataforma headless no pilar de downstream — onde agentes executam, humanos dirigem e a plataforma governa.

## Tese Central

> "SaaS is Dead" — O modelo tradicional de humanos clicando em aplicações está sendo substituído por agentes autônomos operando sobre uma camada de execução governada.

No contexto Oil & Gas Downstream, isso significa:
- **Pricing**: Agentes monitoram Platts/Argus e sugerem preços com guardrails de margem
- **Comercialização B2B**: Cotações geradas via linguagem natural, sem abrir o CRM
- **Fuel Retail**: App headless com Commerce APIs, loyalty e Einstein Recommendations
- **Supply Chain**: Agentes otimizam logística consultando IoT + ERP + CRM
- **Refino**: Tableau Headless gera análises sob demanda para operadores

## Estrutura do Repositório

```
apresentacoes/   — Slides e decks de apresentação
videos/          — Scripts, roteiros e assets de vídeo
materiais/       — Documentos de síntese e análise
  sintese-headless-360.md        — Síntese completa do modelo Headless 360
  headless-oilgas-downstream.md  — Mapeamento para Oil & Gas Downstream
referencias/     — Catálogo de fontes e materiais de referência
  catalogo-fontes.md             — Inventário dos 12+ documentos fonte analisados
assets/          — Imagens, diagramas e recursos visuais
```

## Conceitos Fundamentais

### Arquitetura da Empresa Agêntica
1. **System of Engagement** — Slack (superfície de interação)
2. **System of Agency** — Agentforce (motor de execução)
3. **System of Work** — Customer 360 (lógica e dados)
4. **System of Context** — Data 360 / MuleSoft / Tableau (inteligência)

### Modelo Semi-Determinístico
Nem 100% determinista (BPM tradicional) nem 100% probabilístico (LLM puro):
- Guardrails delimitam o espaço de ação do agente
- Human-in-the-loop para decisões acima de thresholds
- Compliance e validações são determinísticos
- Recomendações e otimizações são probabilísticas com controle

### Doutrina
> "Humans direct, agents execute, the platform governs." — Patrick Stokes

## Fontes Analisadas

- Patrick Stokes — Manifesto "Headless is the Beginning of a New Software Model"
- Data 360 Headless (R. Loganathan) — MCP Server, Trust Layer, Roadmap
- Headless 360 First Call Deck — Visão comercial e arquitetura
- Security & Governance PoV — Agent Fabric, Testing Center, Risk
- Headless Commerce Whitepaper — Arquitetura B2C headless
- Empresas Autónomas (Jorge Arias, Uniandes) — Framework semi-determinístico, 12 regras
