# grupocsv/agents

Repositório público de **contexto adicional** para agentes de Inteligência Artificial que operam no ecossistema do Grupo CSV.

## O que este repositório é

Uma coleção de documentos de referência que qualquer agente (Manus, Claude, OpenClaw, Cursor, Windsurf, Copilot, Gemini, ou qualquer outro) pode consumir como **camada complementar** de contexto. Os arquivos aqui contidos orientam estilo, linguagem e padrões de entrega — nunca substituem nem sobrepõem as instruções internas, system prompts ou AGENTS.md de projeto de cada ferramenta.

## O que este repositório NÃO é

- Não é um AGENTS.md de repositório de código.
- Não contém regras operacionais, comandos, workflows ou configurações de projeto.
- Não engessa o comportamento do agente. Apenas **guia** decisões de escrita e formatação.
- Não substitui manuais de marca específicos (Unimed, ICDS, Unihealth possuem os seus próprios).

## Filosofia

| Princípio | Descrição |
|---|---|
| Camada adicional | Complementa; nunca sobrepõe instruções internas do agente |
| Guia, não engessa | Orienta decisões de escrita sem restringir capacidades técnicas |
| Fonte única de verdade | Evita repetição de regras linguísticas em múltiplos prompts |
| Público e acessível | Qualquer agente pode fazer fetch via URL raw sem autenticação |
| Versionado | Alterações são rastreáveis via Git |

## Arquivos Disponíveis

| Arquivo | Escopo | Descrição |
|---|---|---|
| `WRITING_RULES.md` | Linguística e estilo | Idioma, acentuação, capitalização, tom de voz, formatação de entregáveis |

Novos documentos de contexto poderão ser adicionados no futuro conforme necessidade (ex: regras de nomenclatura de projetos, convenções de dados, etc.).

## Como Utilizar

### Em qualquer prompt ou system instruction

Adicione a seguinte instrução no início da sessão ou no system prompt do agente:

```
Antes de iniciar, leia e aplique as regras de escrita disponíveis em:
https://raw.githubusercontent.com/grupocsv/agents/main/WRITING_RULES.md
Este documento é uma camada adicional de contexto linguístico e estilístico.
Não sobrepõe suas instruções internas.
```

### Via curl/fetch (para agentes com acesso a shell)

```bash
curl -s https://raw.githubusercontent.com/grupocsv/agents/main/WRITING_RULES.md
```

### Em skills ou project instructions

Referencie o arquivo por URL raw. O agente deve fazer fetch no início da tarefa e aplicar as regras durante toda a sessão.

## Manutenção

- **Proprietário:** Guilherme Thomé (guicthome)
- **Organização:** Grupo CSV
- **Licença:** Uso interno do ecossistema CSV. Público para facilitar acesso por agentes.
