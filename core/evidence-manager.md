---

name: evidence-manager
description: Use para planejar, validar, catalogar, filtrar e organizar evidências de projetos, implementações, análises, auditorias e documentações antes da geração de relatórios.
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

---

# Evidence Manager

Especialista na gestão, validação, classificação e preparação de evidências para documentação, auditoria, demonstração e relatórios técnicos.

O objetivo desta skill é garantir que todas as evidências relevantes sejam identificadas, organizadas e preparadas antes da criação da documentação final.

Esta skill segue integralmente os princípios definidos em **Samuel Standards**, garantindo consistência, rastreabilidade e integração com o Samuel Skills System.

---

# Missão

Garantir que:

* Nenhuma evidência importante seja esquecida.
* Nenhuma evidência desnecessária seja mantida.
* Todas as etapas possuam comprovação adequada.
* Todas as evidências estejam organizadas para consumo pelo Technical Report.

---

# Estado 1 — Descoberta

## Objetivo

Compreender o projeto e identificar quais resultados precisam ser comprovados.

## Identificar

* Objetivo do projeto.
* Escopo da atividade.
* Entregáveis esperados.
* Critérios de validação.
* Requisitos de documentação.

## Perguntas Fundamentais

* O que precisa ser comprovado?
* O que precisa ser demonstrado?
* O que precisa ser documentado?
* Quais resultados são obrigatórios?

## Saída Esperada

Plano inicial de evidências necessárias.

---

# Estado 2 — Planejamento de Evidências

## Objetivo

Definir antecipadamente todas as evidências necessárias durante a execução.

## Classificação

### Evidências Obrigatórias

Comprovam requisitos essenciais.

### Evidências Importantes

Fortalecem a documentação técnica.

### Evidências Complementares

Agregam contexto e qualidade ao relatório.

---

## Para cada evidência definir

* Identificação.
* Nome sugerido.
* Objetivo.
* Etapa relacionada.
* Tipo.
* Criticidade.

---

## Exemplo

Figura 1 — Topologia do Ambiente

Figura 2 — Configuração Inicial

Figura 3 — Teste de Conectividade

Figura 4 — Resultado Obtido

Figura 5 — Validação Final

---

## Saída Esperada

Plano de Evidências do Projeto.

---

# Estado 3 — Monitoramento

## Objetivo

Acompanhar a execução do projeto e identificar os momentos que exigem registro de evidências.

## Comportamento

Quando uma etapa relevante for concluída:

1. Identificar a necessidade da evidência.
2. Informar exatamente o que deve ser capturado.
3. Explicar o motivo da captura.
4. Sugerir nome e classificação.

---

## Exemplo

### Evidência Recomendada

Capturar:

* Tela de configuração WAN/LAN.

Nome sugerido:

Figura 3 — Configuração Inicial do pfSense

Motivo:

Comprovação da configuração do firewall.

---

## Saída Esperada

Registro contínuo de evidências durante todo o projeto.

---

# Estado 4 — Auditoria

## Objetivo

Avaliar a qualidade das evidências já coletadas.

## Entradas Aceitas

* Screenshots
* Logs
* Comandos
* Resultados
* Arquivos
* Diagramas
* Tabelas

---

## Classificação

### Manter

Evidência essencial.

### Complementar

Evidência útil.

### Descartar

Evidência redundante ou sem valor documental.

---

## Saída Esperada

Conjunto otimizado de evidências.

---

# Estado 5 — Detecção de Lacunas

## Objetivo

Identificar evidências ausentes antes da geração do relatório.

## Processo

Comparar:

* Evidências planejadas.
* Evidências existentes.

---

## Quando detectar uma lacuna informar

### Evidência Ausente

O que está faltando.

### Justificativa

Por que essa evidência é necessária.

### Como Capturar

* Comando.
* Tela.
* Log.
* Arquivo.
* Resultado esperado.

### Nome Sugerido

Título da futura figura.

---

## Exemplo

Lacuna Detectada

Ausente:

Validação de Conectividade

Capturar:

Comando:

ping

Tela:

Resultado do teste

Nome sugerido:

Figura 5 — Validação de Conectividade

---

## Saída Esperada

Lista completa das evidências faltantes.

---

# Estado 6 — Catalogação

## Objetivo

Organizar todas as evidências aprovadas em um catálogo único.

## Toda evidência deve possuir

### Identificação

Exemplo:

Figura 1

### Título

Figura 1 — Topologia do Ambiente

### Descrição

Resumo da evidência.

### Etapa Relacionada

Fase do projeto.

### Tipo

* Screenshot
* Log
* Comando
* Arquivo
* Diagrama
* Resultado
* Tabela

### Criticidade

* Obrigatória
* Importante
* Complementar

---

## Saída Esperada

Catálogo Oficial de Evidências.

---

# Entrega Final

Ao concluir a análise, apresentar:

## Evidências Obrigatórias

Lista das evidências essenciais.

---

## Evidências Importantes

Lista das evidências recomendadas.

---

## Evidências Complementares

Lista das evidências opcionais.

---

## Evidências Ausentes

Lacunas identificadas.

---

## Evidências Descartadas

Itens removidos e justificativa.

---

## Catálogo Oficial de Evidências

Estrutura pronta para utilização pelo Technical Report.

---

## Recomendações

Orientações para fortalecer a documentação antes da geração do relatório.

---

# Integração com Samuel Core

## Base Comportamental

* samuel-standards

---

## Skills Anteriores Recomendadas

* modo-foco
* project-analyzer
* dependency-validator

---

## Próxima Skill Recomendada

* technical-report

---

## Fluxo Operacional

Modo Foco

↓

Project Analyzer

↓

Dependency Validator

↓

Evidence Manager

↓

Technical Report

---

# Analogia Operacional

Imagine um investigador montando um processo.

Durante a investigação são coletadas dezenas de documentos, fotografias, registros e provas.

Nem tudo será utilizado.

O Evidence Manager atua como esse organizador.

Ele identifica quais evidências realmente comprovam os resultados, elimina redundâncias, detecta lacunas e prepara um catálogo consistente para que o Technical Report utilize apenas as evidências corretas e necessárias.

---

# Resultado Esperado

Ao concluir a gestão das evidências, o usuário deve saber:

* Quais evidências são obrigatórias.
* Quais fortalecem a documentação.
* Quais podem ser descartadas.
* Quais ainda precisam ser capturadas.
* ## Como cada evidência será utilizada na documentação final.

  ## name: evidence-manager description: Use para planejar, validar, catalogar, filtrar e organizar evidências de projetos, implementações, análises, auditorias e documentações antes da geração de relatórios.

  # Evidence Manager

  Especialista na gestão, validação, classificação e preparação de evidências para documentação, auditoria, demonstração e relatórios técnicos.

  O objetivo desta skill é garantir que todas as evidências relevantes sejam identificadas, organizadas e preparadas antes da criação da documentação final.

  ## Esta skill segue integralmente os princípios definidos em **Samuel Standards**, garantindo consistência, rastreabilidade e integração com o Samuel Skills System.

  # Missão

  Garantir que:

  * Nenhuma evidência importante seja esquecida.
  * Nenhuma evidência desnecessária seja mantida.
  * Todas as etapas possuam comprovação adequada.
  * Todas as evidências estejam organizadas para consumo pelo Technical Report.

  ---

  # Estado 1 — Descoberta

  ## Objetivo

  Compreender o projeto e identificar quais resultados precisam ser comprovados.

  ## Identificar

  * Objetivo do projeto.
  * Escopo da atividade.
  * Entregáveis esperados.
  * Critérios de validação.
  * Requisitos de documentação.

  ## Perguntas Fundamentais

  * O que precisa ser comprovado?
  * O que precisa ser demonstrado?
  * O que precisa ser documentado?
  * Quais resultados são obrigatórios?

  ## Saída Esperada

  ## Plano inicial de evidências necessárias.

  # Estado 2 — Planejamento de Evidências

  ## Objetivo

  Definir antecipadamente todas as evidências necessárias durante a execução.

  ## Classificação

  ### Evidências Obrigatórias

  Comprovam requisitos essenciais.

  ### Evidências Importantes

  Fortalecem a documentação técnica.

  ### Evidências Complementares

  ## Agregam contexto e qualidade ao relatório.

  ## Para cada evidência definir

  * Identificação.
  * Nome sugerido.
  * Objetivo.
  * Etapa relacionada.
  * Tipo.
  * Criticidade.

  ---

  ## Exemplo

  Figura 1 — Topologia do Ambiente

  Figura 2 — Configuração Inicial

  Figura 3 — Teste de Conectividade

  Figura 4 — Resultado Obtido

  ## Figura 5 — Validação Final

  ## Saída Esperada

  ## Plano de Evidências do Projeto.

  # Estado 3 — Monitoramento

  ## Objetivo

  Acompanhar a execução do projeto e identificar os momentos que exigem registro de evidências.

  ## Comportamento

  Quando uma etapa relevante for concluída:

  1. Identificar a necessidade da evidência.
  2. Informar exatamente o que deve ser capturado.
  3. Explicar o motivo da captura.
  4. Sugerir nome e classificação.

  ---

  ## Exemplo

  ### Evidência Recomendada

  Capturar:

  * Tela de configuração WAN/LAN.
    Nome sugerido:

  Figura 3 — Configuração Inicial do pfSense

  Motivo:

  ## Comprovação da configuração do firewall.

  ## Saída Esperada

  ## Registro contínuo de evidências durante todo o projeto.

  # Estado 4 — Auditoria

  ## Objetivo

  Avaliar a qualidade das evidências já coletadas.

  ## Entradas Aceitas

  * Screenshots
  * Logs
  * Comandos
  * Resultados
  * Arquivos
  * Diagramas
  * Tabelas

  ---

  ## Classificação

  ### Manter

  Evidência essencial.

  ### Complementar

  Evidência útil.

  ### Descartar

  ## Evidência redundante ou sem valor documental.

  ## Saída Esperada

  ## Conjunto otimizado de evidências.

  # Estado 5 — Detecção de Lacunas

  ## Objetivo

  Identificar evidências ausentes antes da geração do relatório.

  ## Processo

  Comparar:

  * Evidências planejadas.
  * Evidências existentes.

  ---

  ## Quando detectar uma lacuna informar

  ### Evidência Ausente

  O que está faltando.

  ### Justificativa

  Por que essa evidência é necessária.

  ### Como Capturar

  * Comando.
  * Tela.
  * Log.
  * Arquivo.
  * Resultado esperado.

  ### Nome Sugerido

  ## Título da futura figura.

  ## Exemplo

  Lacuna Detectada

  Ausente:

  Validação de Conectividade

  Capturar:

  Comando:

  ping

  Tela:

  Resultado do teste

  Nome sugerido:

  ## Figura 5 — Validação de Conectividade

  ## Saída Esperada

  ## Lista completa das evidências faltantes.

  # Estado 6 — Catalogação

  ## Objetivo

  Organizar todas as evidências aprovadas em um catálogo único.

  ## Toda evidência deve possuir

  ### Identificação

  Exemplo:

  Figura 1

  ### Título

  Figura 1 — Topologia do Ambiente

  ### Descrição

  Resumo da evidência.

  ### Etapa Relacionada

  Fase do projeto.

  ### Tipo

  * Screenshot
  * Log
  * Comando
  * Arquivo
  * Diagrama
  * Resultado
  * Tabela

  ### Criticidade

  * Obrigatória
  * Importante
  * Complementar

  ---

  ## Saída Esperada

  ## Catálogo Oficial de Evidências.

  # Entrega Final

  Ao concluir a análise, apresentar:

  ## Evidências Obrigatórias

  ## Lista das evidências essenciais.

  ## Evidências Importantes

  ## Lista das evidências recomendadas.

  ## Evidências Complementares

  ## Lista das evidências opcionais.

  ## Evidências Ausentes

  ## Lacunas identificadas.

  ## Evidências Descartadas

  ## Itens removidos e justificativa.

  ## Catálogo Oficial de Evidências

  ## Estrutura pronta para utilização pelo Technical Report.

  ## Recomendações

  ## Orientações para fortalecer a documentação antes da geração do relatório.

  # Integração com Samuel Core

  ## Base Comportamental

  * samuel-standards

  ---

  ## Skills Anteriores Recomendadas

  * modo-foco
  * project-analyzer
  * dependency-validator

  ---

  ## Próxima Skill Recomendada

  * technical-report

  ---

  ## Fluxo Operacional

  Modo Foco

  ↓

  Project Analyzer

  ↓

  Dependency Validator

  ↓

  Evidence Manager

  ↓

  ## Technical Report

  # Analogia Operacional

  Imagine um investigador montando um processo.

  Durante a investigação são coletadas dezenas de documentos, fotografias, registros e provas.

  Nem tudo será utilizado.

  O Evidence Manager atua como esse organizador.

  ## Ele identifica quais evidências realmente comprovam os resultados, elimina redundâncias, detecta lacunas e prepara um catálogo consistente para que o Technical Report utilize apenas as evidências corretas e necessárias.

  # Resultado Esperado

  Ao concluir a gestão das evidências, o usuário deve saber:

  * Quais evidências são obrigatórias.
  * Quais fortalecem a documentação.
  * Quais podem ser descartadas.
  * Quais ainda precisam ser capturadas.
  * Como cada evidência será utilizada na documentação final.
