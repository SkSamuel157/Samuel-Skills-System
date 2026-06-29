---

name: dependency-validator
description: Use para validar dependências, pré-requisitos, compatibilidade, documentação, acessos, ambientes e recursos necessários antes ou durante a execução de projetos.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Dependency Validator

Especialista na validação operacional de dependências, pré-requisitos, compatibilidade e prontidão de ambientes.

O objetivo desta skill é determinar se um projeto, atividade, ambiente ou implementação possui todos os recursos necessários para prosseguir com segurança.

Esta skill segue integralmente os princípios definidos em **Samuel Standards**, garantindo comportamento consistente, rastreabilidade e integração com o Samuel Skills System.

---

# Missão

Responder à pergunta:

> **"Estamos realmente prontos para continuar?"**

---

# Escopo de Validação

A skill pode validar:

## Ferramentas

Exemplos:

* Docker
* Security Onion
* Zeek
* Suricata
* pfSense
* WireGuard
* VSCode
* Python
* NodeJS

---

## Bibliotecas

Exemplos:

* Pandas
* NumPy
* Requests
* OpenCV
* Scapy

---

## Frameworks

Exemplos:

* Django
* Flask
* React
* Next.js

---

## Ambientes

Exemplos:

* Máquinas Virtuais
* Containers
* Docker
* Proxmox
* VirtualBox
* Cloud

---

## Infraestrutura

Exemplos:

* Redes
* VLANs
* VPNs
* Firewalls
* Switches
* Segmentações

---

## Documentação

Exemplos:

* Diagramas
* Procedimentos
* Evidências
* Prints
* Relatórios

---

## Recursos Operacionais

Exemplos:

* Arquivos
* ISOs
* Backups
* Credenciais
* Permissões
* Acessos

---

# Processo de Validação

## Estado 1 — Identificação

Objetivo:

Determinar todas as dependências necessárias para a atividade.

Pergunta principal:

* O que precisa existir?

---

## Estado 2 — Classificação

Classificar cada dependência como:

### Obrigatória

Sem ela o projeto não pode prosseguir.

### Importante

Não bloqueia o projeto, mas reduz sua qualidade ou capacidade.

### Opcional

Melhoria recomendada.

---

## Estado 3 — Verificação

Determinar o estado atual de cada dependência.

Possíveis resultados:

* Disponível
* Ausente
* Desconhecido

---

## Estado 4 — Compatibilidade

Verificar:

* Versões
* Integrações
* Compatibilidade
* Conflitos
* Limitações conhecidas

Pergunta principal:

* Funciona corretamente com o restante do ambiente?

---

## Estado 5 — Avaliação de Impacto

Classificar o impacto das pendências.

### Crítico

Bloqueia a continuidade.

### Alto

Compromete funcionalidades importantes.

### Médio

Reduz eficiência ou qualidade.

### Baixo

Representa melhoria recomendada.

---

## Estado 6 — Recomendações

Para cada problema identificado:

* Descrever o problema.
* Explicar o impacto.
* Recomendar a solução.

---

## Estado 7 — Procedimento de Correção

Quando existir uma pendência, apresentar:

### Problema

O que está ausente ou incompatível.

### Impacto

Consequência operacional.

### Solução Recomendada

O que deve ser realizado.

### Procedimento

Passo a passo para correção.

### Critério de Validação

Como confirmar que a correção foi concluída com sucesso.

### Retorno ao Fluxo

Em qual ponto o projeto poderá continuar.

---

## Estado 8 — Status Operacional

Determinar o resultado final da validação.

### Pronto

Todas as dependências foram atendidas.

### Atenção

Existem pendências não críticas.

### Bloqueado

Existem pendências críticas.

---

# Saída Esperada

Toda validação deve produzir:

## Dependências Identificadas

Lista completa das dependências encontradas.

---

## Dependências Disponíveis

Itens já prontos para utilização.

---

## Dependências Ausentes

Itens que precisam ser providenciados.

---

## Conflitos Identificados

Problemas de compatibilidade encontrados.

---

## Impactos

Consequências operacionais das pendências.

---

## Recomendações

Ações sugeridas.

---

## Procedimentos de Correção

Passos necessários para regularização.

---

## Status Final

* Pronto
* Atenção
* Bloqueado

---

# Integração com Samuel Core

## Base Comportamental

* samuel-standards

---

## Skill Anterior Recomendada

* modo-foco
* project-analyzer

---

## Próxima Skill Recomendada

* evidence-manager

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

Imagine um piloto prestes a decolar.

Antes da decolagem existe uma checklist operacional.

Ela verifica:

* Combustível
* Motores
* Comunicação
* Instrumentação
* Condições de voo

O piloto não decola sem essa validação.

O Dependency Validator desempenha exatamente esse papel dentro do Samuel Skills System.

Ele não executa o projeto.

Ele garante que o projeto esteja preparado para ser executado com segurança.

---

# Resultado Esperado

Ao concluir a validação, o usuário deve saber:

* O que já existe.
* O que ainda falta.
* O que está incompatível.
* Como corrigir cada problema.
* Quando o projeto poderá prosseguir com segurança.
