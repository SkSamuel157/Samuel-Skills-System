# Phase Controller

> Componente responsável por controlar as fases de interação entre usuário e Samuel Skills System.

---

# Visão Geral

O Phase Controller garante que cada momento da interação tenha um propósito claro.

Sua função é impedir que discussões, decisões, execuções e validações sejam misturadas na mesma etapa.

O Phase Controller não decide o fluxo operacional nem executa tarefas. Ele apenas controla a fase atual da interação.

---

# Missão

Garantir que a conversa avance de forma organizada, respeitando o estado atual da interação.

---

# Responsabilidades

O Phase Controller é responsável por:

- identificar a fase atual da interação;
- separar momentos de discussão e execução;
- impedir recomendações após uma decisão já confirmada;
- garantir que uma etapa seja concluída antes da próxima iniciar;
- manter clareza sobre o momento atual do trabalho.

---

# Fases da Interação

## 1. Discussão

Utilizada para:

- analisar possibilidades;
- apresentar alternativas;
- explicar impactos;
- recomendar abordagens.

Nesta fase, nenhuma alteração deve ser executada.

---

## 2. Decisão

Representa o momento em que o usuário aprova um caminho.

Após uma decisão:

- a discussão é encerrada;
- novas alternativas não devem ser apresentadas;
- o fluxo deve avançar para execução.

---

## 3. Execução

Representa a realização do que foi decidido.

Durante execução:

- seguir o plano aprovado;
- evitar novas recomendações fora do escopo;
- executar apenas a etapa atual.

---

## 4. Validação

Confirma se a execução atingiu o resultado esperado.

Durante validação:

- verificar resultado;
- identificar erros;
- confirmar conclusão;
- liberar próxima etapa.

---

# Fluxo Operacional

Discussão

↓

Decisão

↓

Execução

↓

Validação

↓

Próxima Etapa

Cada fase deve ser concluída antes da próxima iniciar.

---

# Entradas

O Phase Controller pode receber:

- estado atual da conversa;
- intenção do usuário;
- confirmação de decisão;
- resultado de execução.

---

# Processamento

Durante sua execução, o Phase Controller:

1. identifica a fase atual;
2. verifica se houve mudança de fase;
3. impede retorno desnecessário para fases anteriores;
4. mantém a interação alinhada ao momento correto.

---

# Saídas

O módulo fornece:

- fase atual identificada;
- autorização para continuidade;
- indicação de mudança de fase.

---

# Integração

O Phase Controller integra-se com:

- Interaction Workflow;
- Core Engine;
- Operational Status.

---

# Limitações

O Phase Controller não:

- escolhe Skills;
- executa ações;
- valida conteúdo técnico;
- altera estado global;
- cria pipelines.

Sua responsabilidade é apenas controlar a fase da interação.

---

# Futuro

Evoluções futuras podem incluir:

- fases customizadas por tipo de projeto;
- identificação automática de intenção;
- adaptação dinâmica do fluxo de interação.