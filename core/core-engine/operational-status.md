# Operational Status

> Módulo responsável por comunicar ao usuário o estado operacional do projeto durante a execução do Samuel Skills System.

---

# Visão Geral

O Operational Status atua como a camada de comunicação entre o Core Engine e o usuário.

Sua função é traduzir o estado interno do sistema em informações claras, objetivas e úteis, permitindo que o usuário compreenda o andamento do projeto sem precisar conhecer a arquitetura interna do Samuel Skills System.

O Operational Status não participa das decisões do sistema nem executa qualquer atividade operacional.

---

# Missão

Comunicar o estado atual do projeto de forma simples, consistente e contextualizada, preservando a abstração da arquitetura interna.

---

# Responsabilidades

O Operational Status é responsável por:

- informar o estado atual do projeto;
- comunicar a fase operacional em andamento;
- apresentar o objetivo imediato da etapa atual;
- indicar a próxima ação esperada do usuário quando necessário;
- comunicar bloqueios, pendências e conclusões;
- adaptar o nível de detalhe da comunicação ao contexto da conversa.

---

# Fluxo Operacional

```
Receber Estado Global

↓

Identificar Situação Atual

↓

Traduzir para Linguagem Operacional

↓

Comunicar ao Usuário
```

O Operational Status nunca expõe detalhes internos do Core Engine.

---

# Entradas

O Operational Status pode receber:

- estado global;
- fase atual;
- pipeline em execução;
- eventos relevantes;
- informações do Core Engine.

---

# Processamento

Durante sua execução, o Operational Status:

1. consulta o estado atual do projeto;
2. identifica a informação relevante para o usuário;
3. traduz o estado interno para uma linguagem simples;
4. comunica apenas o necessário para orientar a continuidade do trabalho.

O módulo evita expor detalhes técnicos internos que não agreguem valor ao usuário.

---

# Saídas

O módulo fornece:

- estado operacional atual;
- objetivo da etapa em execução;
- orientação para a próxima ação;
- mensagens de conclusão, bloqueio ou continuidade.

---

# Integração

O Operational Status integra-se diretamente com:

- Core Engine;
- State Manager;
- Pipeline Builder;
- Transition Manager.

O módulo utiliza as informações fornecidas pelos demais componentes para produzir uma comunicação consistente ao usuário.

---

# Limitações

O Operational Status não:

- executa Skills;
- altera o estado global;
- constrói pipelines;
- valida consistência;
- registra histórico;
- toma decisões operacionais.

Sua responsabilidade limita-se exclusivamente à comunicação do estado operacional.

---

# Futuro

Nas próximas versões, o Operational Status poderá evoluir para suportar:

- diferentes níveis de detalhamento da comunicação;
- modos de operação (desenvolvimento e produção);
- adaptação automática ao perfil do usuário;
- personalização da apresentação do progresso do projeto.