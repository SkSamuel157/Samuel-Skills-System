# ROUTER

Sistema oficial de roteamento do Samuel Skills System.

Este documento determina qual skill deve ser utilizada conforme o objetivo do usuário, a complexidade da solicitação e o estado atual do projeto.

Seu objetivo é garantir que cada responsabilidade seja executada pela skill correta.

---

# Processo de Decisão

Antes de responder qualquer solicitação:

1. Compreender o objetivo do usuário.
2. Identificar a complexidade da solicitação.
3. Determinar o estado atual do projeto.
4. Selecionar a skill mais adequada.
5. Executar apenas as skills necessárias.

---

# Níveis de Complexidade

## Nível 1 — Simples

Exemplos:

* Perguntas rápidas.
* Definições.
* Pequenas explicações.
* Correções pontuais.

### Ação

Responder diretamente.

Não utilizar o Samuel Core, salvo solicitação explícita.

---

## Nível 2 — Moderado

Exemplos:

* Pequenos planejamentos.
* Ajustes em documentos.
* Melhorias em projetos.
* Análises específicas.

### Ação

Utilizar apenas a skill responsável pela tarefa.

Evitar iniciar todo o fluxo do Samuel Core.

---

## Nível 3 — Complexo

Exemplos:

* Projetos completos.
* Trabalhos acadêmicos.
* Ambientes corporativos.
* Implementações.
* Arquiteturas.
* Relatórios técnicos.

### Ação

Executar o fluxo recomendado pelo Samuel Core.

---

# Seleção de Skills

## O usuário deseja iniciar um novo projeto

Utilizar:

Modo Foco

---

## O usuário recebeu um projeto já existente

Utilizar:

Project Analyzer

Após compreender o cenário:

Modo Foco

---

## O usuário precisa entender um ambiente

Utilizar:

Project Analyzer

---

## O usuário precisa localizar sua responsabilidade dentro de um projeto

Utilizar:

Project Analyzer

---

## O usuário deseja planejar um projeto

Utilizar:

Modo Foco

---

## O usuário está executando um projeto

Continuar utilizando:

Modo Foco

---

## Surgiu uma nova ferramenta, biblioteca, framework ou requisito

Utilizar:

Dependency Validator

Após a validação:

Retornar exatamente ao fluxo anterior.

---

## O usuário deseja verificar se o ambiente está pronto

Utilizar:

Dependency Validator

---

## O usuário deseja organizar evidências

Utilizar:

Evidence Manager

---

## O usuário deseja saber quais evidências ainda faltam

Utilizar:

Evidence Manager

---

## O usuário deseja gerar documentação

Utilizar:

Technical Report

---

## O usuário deseja criar uma nova skill

Utilizar:

Skill Creator

---

## O usuário deseja evoluir uma skill existente

Utilizar:

Skill Creator

---

# Fluxos Recomendados

## Projeto Novo

Ideia

↓

Modo Foco

↓

Dependency Validator (quando necessário)

↓

Execução

↓

Evidence Manager

↓

Technical Report

---

## Projeto Existente

Projeto

↓

Project Analyzer

↓

Modo Foco

↓

Dependency Validator

↓

Execução

↓

Evidence Manager

↓

Technical Report

---

## Criação de Skill

Necessidade

↓

Skill Creator

↓

Nova Skill

↓

Integração ao Samuel Skills System

---

## Documentação

Projeto Finalizado

↓

Evidence Manager

↓

Technical Report

---

# Integração entre Skills

As skills são complementares.

Uma skill nunca substitui outra quando ambas possuem responsabilidades distintas.

Quando múltiplas skills forem necessárias, executá-las na sequência recomendada.

---

# Retorno ao Fluxo

Sempre que uma skill intermediária for utilizada (como Dependency Validator ou Evidence Manager), retornar ao ponto exato do fluxo onde o projeto foi interrompido.

---

# Encerramento

Considerar um fluxo concluído apenas quando:

* o objetivo principal for atingido; ou
* o usuário solicitar explicitamente o encerramento.

---

# Objetivo Final

Garantir que toda solicitação seja encaminhada para a skill mais adequada, utilizando o menor número de etapas necessário e preservando o contexto durante todo o ciclo do projeto.
