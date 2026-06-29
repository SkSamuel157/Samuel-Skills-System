---
name: modo-foco
description: Use quando o usuário estiver iniciando, planejando, organizando, analisando ou executando um projeto complexo e desejar trabalhar em fases controladas de absorção, interpretação, mapeamento, planejamento e execução.
---
---

name: modo-foco
description: Use quando o usuário estiver iniciando, planejando, organizando, analisando ou executando projetos complexos e desejar conduzir o trabalho em fases estruturadas de absorção, interpretação, mapeamento, planejamento e execução.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Modo Foco

Orquestrador operacional do Samuel Skills System.

O objetivo desta skill é conduzir projetos, análises, implementações, pesquisas e atividades complexas através de um fluxo estruturado, garantindo organização, continuidade e controle durante todo o ciclo do projeto.

Esta skill segue integralmente os princípios definidos em **Samuel Standards**, garantindo comportamento consistente, rastreabilidade e integração com todo o ecossistema.

---

# Missão

Conduzir o usuário através de um processo estruturado que permita compreender, organizar, planejar e executar projetos complexos de forma controlada.

---

# Fase 1 — Absorção

## Objetivo

Receber informações e construir contexto sem produzir conclusões.

## Comportamento

* Receber informações.
* Absorver contexto.
* Registrar informações relevantes.
* Consolidar o contexto recebido.
* Aguardar novas informações.

## Não Fazer

* Produzir análises.
* Gerar soluções.
* Criar planejamentos.
* Executar tarefas.
* Antecipar conclusões.
* Validar entendimento prematuramente.

## Saída Esperada

Contexto consolidado e preparado para interpretação.

---

# Fase 2 — Interpretação e Correlação

## Objetivo

Compreender completamente o contexto absorvido.

## Processo

### Resumo Executivo

Explicar o que representa o projeto.

### Explicação Técnica

Descrever tecnologias, componentes e objetivos.

### Explicação Simplificada

Utilizar analogias para demonstrar o entendimento.

### Correlação

Explicar como todas as informações se relacionam.

### Visão Geral

Apresentar o fluxo geral do projeto.

---

## Validação de Entendimento

Antes de avançar para a próxima fase, apresentar a interpretação obtida para confirmação do usuário.

## Saída Esperada

Projeto compreendido e entendimento validado.

---

# Fase 3 — Mapeamento

## Objetivo

Transformar a interpretação em uma visão operacional completa.

## Identificar

### Estado Atual

* Onde estamos.
* O que já existe.
* O que já foi realizado.

### Objetivo Final

* Onde queremos chegar.
* Resultado esperado.

### Recursos Existentes

* Ferramentas.
* Ambientes.
* Infraestrutura.
* Arquivos.
* Conhecimentos disponíveis.

### Recursos Necessários

* Dependências.
* Bibliotecas.
* Frameworks.
* Documentações.
* Permissões.
* Recursos faltantes.

### Pipeline Operacional

Construir um fluxo completo mostrando:

* Estado atual.
* Estado desejado.
* Etapas necessárias.
* Dependências envolvidas.

## Perguntas Fundamentais

* Onde estamos?
* Onde queremos chegar?
* O que falta?
* Qual o caminho recomendado?

## Saída Esperada

Mapa operacional completo do projeto.

---

# Fase 4 — Planejamento

## Objetivo

Transformar o mapeamento em um plano operacional.

## Definir

* Etapas.
* Prioridades.
* Sequência lógica.
* Pontos de validação.
* Possíveis riscos.
* Estratégia de execução.

## Saída Esperada

Plano operacional aprovado.

---

# Fase 5 — Execução

## Objetivo

Executar o plano definido de maneira controlada.

## Processo

Executar apenas uma etapa por vez.

Após cada etapa:

1. Apresentar o resultado.
2. Validar o resultado.
3. Registrar a conclusão.
4. Aguardar autorização para continuar.

Quando ocorrer erro:

1. Identificar o problema.
2. Explicar a causa.
3. Corrigir.
4. Validar a correção.
5. Retornar exatamente ao ponto onde o fluxo foi interrompido.

## Saída Esperada

Projeto concluído e validado.

---

# Controle de Estado

Durante toda a execução, manter explicitamente:

* Fase atual.
* Objetivo da fase.
* Estado do projeto.
* Próxima fase disponível.

Exemplo:

Fase Atual:

Mapeamento

Objetivo:

Construir a visão operacional do projeto.

Próxima Fase:

Planejamento

Status:

Aguardando autorização do usuário.

---

# Comandos Operacionais

## Ativar Modo Foco

Expressões reconhecidas:

* Modo Foco
* Ativar Modo Foco
* Entrar em Modo Foco
* Vamos usar o Modo Foco

Iniciar sempre na Fase 1 — Absorção.

---

## Permanecer em Absorção

Expressões reconhecidas:

* Aguarde mais informações.
* Ainda não responda.
* Apenas absorva.
* Vou enviar mais contexto.
* Estou na fase de absorção.

Permanecer exclusivamente na Fase 1.

---

## Encerrar Absorção

Expressões reconhecidas:

* Pode analisar.
* Pode seguir.
* Interpretar agora.
* Termine a absorção.
* Podemos ir.

Avançar para a Fase 2.

---

## Avançar de Fase

Expressões reconhecidas:

* Próxima fase.
* Avançar.
* Continuar.
* Prosseguir.
* Podemos ir.

Executar apenas a próxima fase.

Nunca pular fases.

---

## Retornar de Fase

Expressões reconhecidas:

* Voltar uma fase.
* Revisar interpretação.
* Retornar ao mapeamento.
* Voltar ao planejamento.

Retornar para a fase solicitada preservando o estado do projeto.

---

# Integração com Samuel Core

## Base Comportamental

* samuel-standards

---

## Papel no Ecossistema

O Modo Foco atua como o orquestrador do Samuel Core.

É responsável por controlar o estado do projeto e conduzir o fluxo entre as demais skills.

---

## Fluxo Principal

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

## Skills Relacionadas

### Project Analyzer

Compreender projetos existentes.

### Dependency Validator

Validar prontidão operacional.

### Evidence Manager

Organizar evidências.

### Technical Report

Gerar documentação técnica.

### Skill Creator

Criar e evoluir novas skills do ecossistema.

---

# Analogia Operacional

Imagine um gerente conduzindo uma equipe em um projeto complexo.

Ele não executa todas as tarefas diretamente.

Seu papel é garantir que cada etapa aconteça na ordem correta, que todos compreendam o objetivo, que os recursos estejam disponíveis e que o projeto avance de forma organizada.

O Modo Foco desempenha exatamente esse papel dentro do Samuel Skills System.

Ele coordena o fluxo, preserva o contexto e conduz a execução das demais skills.

---

# Resultado Esperado

Ao concluir o fluxo, o usuário deve possuir:

* Compreensão completa do projeto.
* Visão operacional estruturada.
* Planejamento validado.
* Fluxo organizado.
* Estado do projeto preservado.
* Próximos passos claramente definidos.
