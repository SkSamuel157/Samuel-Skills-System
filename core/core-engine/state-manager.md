# State Manager

> Módulo responsável por manter o estado global do projeto durante todo o ciclo de vida do Samuel Skills System.

---

# Visão Geral

O State Manager é responsável por armazenar e atualizar a representação única do estado do projeto.

Todos os módulos do Core Engine consultam ou atualizam este estado durante sua execução.

O State Manager não toma decisões, não executa Skills e não interpreta solicitações do usuário.

Sua única responsabilidade é preservar um estado consistente e compartilhado entre todos os componentes do sistema.

---

# Missão

Garantir que todo o Samuel Skills System trabalhe sobre uma única fonte de verdade para o estado atual do projeto.

---

# Responsabilidades

O State Manager é responsável por:

- manter o objetivo principal do projeto;
- registrar o estado atual da execução;
- armazenar a Skill atualmente em execução;
- registrar a Skill anteriormente executada;
- indicar a próxima Skill selecionada pelo Core Engine;
- manter o pipeline atual;
- registrar dependências identificadas;
- registrar pendências;
- registrar decisões relevantes;
- manter o progresso geral do projeto.

---

# Fluxo Operacional

```
Receber atualização

↓

Validar integridade

↓

Atualizar Estado Global

↓

Disponibilizar novo estado aos demais módulos
```

O State Manager nunca modifica informações por iniciativa própria.

Toda atualização deve ser originada por outro componente autorizado do Core Engine.

---

# Entradas

O State Manager pode receber:

- objetivo do projeto;
- atualizações do Core Engine;
- mudanças de estado;
- alterações de pipeline;
- eventos relevantes;
- informações produzidas pelas Skills.

---

# Processamento

Ao receber uma atualização, o State Manager:

1. identifica o elemento que será atualizado;
2. verifica a integridade da informação;
3. preserva a consistência do estado global;
4. registra a atualização;
5. disponibiliza imediatamente o novo estado aos demais módulos.

O State Manager não interpreta o significado das informações.

---

# Saídas

O módulo fornece aos demais componentes:

- estado global atualizado;
- objetivo atual;
- Skill atual;
- Skill anterior;
- próxima Skill;
- pipeline atual;
- progresso do projeto;
- dependências registradas;
- pendências;
- decisões armazenadas.

---

# Integração

O State Manager integra-se diretamente com:

- Core Engine;
- Pipeline Builder;
- Transition Manager;
- Continuity Manager;
- Operational Status;
- History Manager;
- Consistency Validator.

Todos os módulos consultam o State Manager antes de executar suas responsabilidades.

---

# Limitações

O State Manager não:

- decide o fluxo do projeto;
- seleciona Skills;
- interpreta solicitações;
- valida consistência;
- produz relatórios;
- executa tarefas especializadas.

Sua responsabilidade limita-se exclusivamente à manutenção do estado global.

---

# Futuro

Nas próximas versões, o State Manager poderá evoluir para suportar:

- versionamento interno do estado;
- recuperação de estados anteriores;
- snapshots de execução;
- persistência entre sessões;
- sincronização entre múltiplos fluxos.