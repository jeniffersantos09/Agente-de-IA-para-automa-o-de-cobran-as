# Agente de IA para automação de cobranças

**Status:** em produção · em andamento

Agente que entende pedidos em linguagem natural e consulta inadimplências e pagamentos.

**Tecnologias:** Python, FastAPI, MySQL, tool calling

## Problema

Consultar inadimplências e executar ações de cobrança exigia buscar os dados manualmente em vários lugares.

## O que fiz

- Construí um agente que interpreta pedidos em linguagem natural e escolhe a ferramenta certa (tool calling).
- Integrei o agente ao MySQL para consultar inadimplências e pagamentos e executar ações de cobrança.
- Criei um fluxo human-in-the-loop: o agente pede confirmação antes de qualquer ação sensível.
- Disponibilizei tudo como API REST com FastAPI.
