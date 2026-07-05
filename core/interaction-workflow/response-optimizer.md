# Response Optimizer

> Componente responsável por ajustar o nível de detalhe das respostas do Samuel Skills System.

---

# Visão Geral

O Response Optimizer garante que cada resposta tenha a quantidade adequada de informação para o momento atual.

Sua função é evitar respostas excessivamente longas em situações simples e garantir explicações completas quando o contexto exigir.

O Response Optimizer não altera decisões, execução ou funcionamento das Skills.

Ele controla apenas a forma e profundidade da resposta apresentada ao usuário.

---

# Missão

Fornecer respostas proporcionais ao contexto, mantendo clareza sem prejudicar o ritmo da interação.

---

# Responsabilidades

O Response Optimizer é responsável por:

- identificar o nível de detalhe necessário;
- reduzir explicações quando a validação for simples;
- expandir explicações quando houver complexidade;
- evitar repetição de informações já conhecidas;
- preservar fluidez durante execuções contínuas.

---

# Níveis de Resposta

## Resposta Objetiva

Utilizada quando:

- a etapa é simples;
- o usuário já possui contexto suficiente;
- existe apenas necessidade de validação;
- não há erro encontrado.

Exemplo:

```
Validação concluída.

Nenhum erro encontrado.

Próxima etapa: executar X.
```

Não deve incluir explicações detalhadas desnecessárias.

---

## Resposta Explicativa

Utilizada quando:

- existe novo conceito;
- existe decisão arquitetural;
- o usuário solicita entendimento;
- há risco de executar sem compreender.

Exemplo:

```
Antes de alterar isso, precisamos entender o impacto dessa mudança porque ela afeta outros componentes.
```

---

## Resposta de Erro

Utilizada quando:

- algo falhou;
- existe inconsistência;
- existe bloqueio.

Deve explicar:

- o problema encontrado;
- o motivo;
- a correção necessária.

---

# Regra de Proporcionalidade

O tamanho da resposta deve acompanhar a complexidade da situação.

Baixa complexidade:

```
Validar → Confirmar → Continuar
```

Alta complexidade:

```
Contextualizar

↓

Explicar

↓

Executar

↓

Validar
```

---

# Evitar Sobrecarga

O sistema deve evitar:

- explicar conceitos já compreendidos;
- repetir decisões já tomadas;
- transformar validações simples em documentação;
- adicionar contexto que não auxilia a etapa atual.

---

# Entradas

O Response Optimizer pode receber:

- fase atual;
- histórico da conversa;
- complexidade da tarefa;
- necessidade de explicação.

---

# Processamento

Durante sua execução, o Response Optimizer:

1. identifica o objetivo da resposta;
2. avalia a complexidade da situação;
3. seleciona o nível adequado de detalhe;
4. produz uma resposta proporcional.

---

# Saídas

O módulo fornece:

- nível de detalhamento;
- formato recomendado da resposta;
- quantidade adequada de contexto.

---

# Integração

O Response Optimizer integra-se com:

- Interaction Workflow;
- Execution Flow Controller;
- Communication Adapter;
- Operational Status.

---

# Limitações

O Response Optimizer não:

- remove informações críticas;
- altera decisões técnicas;
- ignora erros;
- modifica pipelines.

Sua responsabilidade é apenas otimizar a apresentação da resposta.

---

# Futuro

Evoluções futuras podem incluir:

- perfis personalizados de detalhamento;
- ajuste automático ao usuário;
- modos resumido, técnico e didático.