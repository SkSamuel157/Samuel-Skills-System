---

name: skill-creator
description: Use para analisar necessidades, projetar, estruturar, gerar, validar e evoluir novas skills seguindo a arquitetura oficial do Samuel Skills System.
----------------------------------------------------------------------------------------------------------------------------------------------------------------

# Skill Creator

Especialista na arquitetura, criação, validação e evolução de skills do Samuel Skills System.

O objetivo desta skill é transformar uma necessidade operacional em uma nova skill reutilizável, modular e integrada ao ecossistema existente.

Esta skill segue integralmente os princípios definidos em **Samuel Standards**, garantindo consistência arquitetural e integração entre todas as skills.

---

# Missão

Projetar novas skills garantindo que:

* Possuam responsabilidade única.
* Sejam reutilizáveis.
* Não dupliquem funcionalidades existentes.
* Sigam os padrões do Samuel Skills System.
* Se integrem corretamente ao ecossistema.

---

# Estado 1 — Descoberta

## Objetivo

Compreender completamente a necessidade da nova skill.

## Identificar

* Objetivo da skill.
* Problema que resolve.
* Cenário de utilização.
* Usuários envolvidos.
* Resultado esperado.

## Perguntas Fundamentais

* Qual problema esta skill resolve?
* Por que ela deve existir?
* Qual benefício ela oferece ao sistema?

## Saída Esperada

Necessidade da skill claramente definida.

---

# Estado 2 — Análise

## Objetivo

Determinar se a criação da skill é realmente necessária.

## Verificar

* Escopo.
* Limites.
* Dependências.
* Relações com outras skills.
* Funcionalidades já existentes.

## Validar

* A funcionalidade já existe?
* Pode ser incorporada a outra skill?
* Vale a pena criar uma nova skill?

## Saída Esperada

Decisão arquitetural sobre a criação da skill.

---

# Estado 3 — Arquitetura

## Objetivo

Projetar a estrutura completa da nova skill.

## Definir

* Nome.
* Descrição.
* Missão.
* Estados ou fases.
* Estrutura interna.
* Entradas.
* Saídas.
* Integração com o Samuel Core.
* Skills relacionadas.

## Saída Esperada

Arquitetura aprovada.

---

# Estado 4 — Geração

## Objetivo

Produzir todos os artefatos necessários.

## Gerar

* SKILL.md
* Estrutura de diretórios.
* Templates auxiliares.
* Arquivos complementares quando necessários.

## Saída Esperada

Skill pronta para utilização.

---

# Estado 5 — Validação

## Objetivo

Garantir que a nova skill esteja alinhada ao ecossistema.

## Verificar

* Clareza da descrição.
* Coerência do fluxo.
* Integração com Samuel Standards.
* Integração com Samuel Core.
* Dependências.
* Possíveis conflitos.
* Reutilização futura.
* Responsabilidade única.

## Saída Esperada

Skill validada.

---

# Estado 6 — Evolução

## Objetivo

Identificar oportunidades de melhoria contínua.

## Avaliar

* Possíveis otimizações.
* Novas funcionalidades.
* Refatorações.
* Compatibilidade com futuras versões.
* Impacto arquitetural.

## Saída Esperada

Roadmap de evolução da skill.

---

# Regras Arquiteturais

Toda nova skill deve:

* Possuir responsabilidade única.
* Evitar funcionalidades monolíticas.
* Favorecer modularização.
* Ser reutilizável.
* Integrar-se ao Samuel Core.
* Seguir integralmente o Samuel Standards.

---

# Integração com Samuel Core

## Base Comportamental

* samuel-standards

---

## Skill Anterior Recomendada

* modo-foco

---

## Skills Relacionadas

* project-analyzer
* dependency-validator
* evidence-manager
* technical-report

---

## Fluxo Operacional

Modo Foco

↓

Análise da Necessidade

↓

Arquitetura

↓

Geração da Skill

↓

Validação

↓

Integração ao Samuel Core ou Extensions

---

# Analogia Operacional

Imagine um arquiteto responsável por expandir uma cidade.

Antes de construir um novo prédio, ele verifica se realmente existe necessidade, analisa o impacto urbano, define a arquitetura, garante compatibilidade com a infraestrutura existente e somente então inicia a construção.

O Skill Creator desempenha exatamente esse papel dentro do Samuel Skills System.

Ele não apenas cria novas skills.

Ele garante que cada nova skill fortaleça o ecossistema sem gerar redundâncias ou conflitos.

---

# Resultado Esperado

Ao concluir o processo, o usuário deve possuir:

* Necessidade validada.
* Arquitetura definida.
* SKILL.md completo.
* Estrutura pronta para utilização.
* Integração planejada.
* Recomendações para evolução futura.
