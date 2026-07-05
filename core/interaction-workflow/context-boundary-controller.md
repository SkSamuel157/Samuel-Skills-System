# Context Boundary Controller

> Componente responsável por controlar os limites de contexto durante mudanças de objetivo no Samuel Skills System.

---

# Visão Geral

O Context Boundary Controller garante que mudanças de objetivo sejam tratadas sem mistura indevida entre fluxos diferentes.

Sua função é separar o contexto que deve ser preservado internamente das informações que devem aparecer na comunicação com o usuário.

O Context Boundary Controller não apaga histórico nem altera decisões anteriores.

Ele controla apenas quais informações continuam relevantes para o fluxo atual.

---

# Missão

Garantir continuidade quando necessário e isolamento quando houver mudança explícita de objetivo.

---

# Responsabilidades

O Context Boundary Controller é responsável por:

- identificar mudanças de objetivo;
- separar fluxos independentes;
- preservar contexto ainda relevante;
- evitar reutilização indevida de informações antigas;
- impedir referências desnecessárias a fluxos encerrados.

---

# Tipos de Contexto

## Contexto Ativo

Informações diretamente relacionadas ao objetivo atual.

Deve ser utilizado normalmente durante a execução.

Exemplos:

- objetivo atual;
- decisões válidas;
- etapa em andamento;
- dependências atuais.

---

## Contexto Histórico

Informações pertencentes a fluxos anteriores.

Deve ser preservado para rastreabilidade, mas não deve influenciar automaticamente novos fluxos.

Exemplos:

- projetos encerrados;
- objetivos substituídos;
- decisões antigas sem relação atual.

---

# Mudança de Objetivo

Quando o usuário indicar mudança explícita:

Exemplos:

- "esqueça isso";
- "na verdade quero fazer outra coisa";
- "vamos mudar o objetivo".

O sistema deve:

1. encerrar o fluxo anterior;
2. identificar o novo objetivo;
3. preservar apenas informações necessárias;
4. iniciar o novo fluxo sem misturar contextos.

---

# Comunicação Após Mudança

Evitar:

Considerando tudo que fizemos anteriormente...

quando o histórico anterior não for necessário.

Preferir:

Novo objetivo identificado.

Vamos iniciar esta etapa.

A continuidade interna deve existir sem criar dependência visual desnecessária para o usuário.

---

# Entradas

O Context Boundary Controller pode receber:

- histórico da conversa;
- objetivo anterior;
- novo objetivo;
- estado atual.

---

# Processamento

Durante sua execução, o Context Boundary Controller:

1. identifica se houve mudança de objetivo;
2. classifica contexto ativo e histórico;
3. define quais informações permanecem relevantes;
4. limita exposição de contexto antigo.

---

# Saídas

O módulo fornece:

- contexto ativo atualizado;
- separação entre fluxos;
- comunicação alinhada ao objetivo atual.

---

# Integração

O Context Boundary Controller integra-se com:

- Interaction Workflow;
- Continuity Manager;
- State Manager;
- Operational Status.

---

# Limitações

O Context Boundary Controller não:

- remove histórico permanente;
- altera decisões tomadas;
- modifica pipelines;
- executa Skills.

Sua responsabilidade é apenas controlar fronteiras de contexto.

---

# Futuro

Evoluções futuras podem incluir:

- múltiplos contextos paralelos;
- alternância entre projetos;
- recuperação inteligente de fluxos antigos;
- classificação avançada de relevância.