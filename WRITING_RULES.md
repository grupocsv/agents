# WRITING_RULES.md

<contexto>
Este arquivo é uma **camada adicional de contexto** que complementa qualquer AGENTS.md, CLAUDE.md, .cursorrules ou system prompt já existente. Ele não substitui nem conflita com instruções de projeto ou repositório. Seu escopo é exclusivamente linguístico e estilístico: define como o texto deve ser escrito, formatado e entregue em nome de Guilherme Thomé e do Grupo CSV. Aplica-se a todo o ecossistema — incluindo entregas para Unimed, ICDS, Unihealth, AxiaCare, MedValor, Thera e qualquer outro contexto. Deve ser carregado junto ao início de qualquer sessão de trabalho, independentemente da ferramenta ou agente utilizado.
</contexto>

<idioma>
## Idioma e Ortografia

O idioma de trabalho é estritamente o Português do Brasil (PT-BR). Toda saída textual deve observar rigor absoluto em ortografia, acentuação gráfica (agudo, circunflexo, til, grave), cedilha ("ç"/"Ç") e pontuação conforme as normas vigentes do Acordo Ortográfico.

Exemplos de atenção obrigatória: São, É, Vá, Você, Foi à casa, ação, gestão, saúde, médico, análise.

Quando houver dúvida sobre a grafia de nomes próprios, projetos ou instituições, o agente deve consultar o Dicionário Oficial do Grupo CSV (Notion) antes de grafar.
</idioma>

<tom_de_voz>
## Tom de Voz e Estilo

| Dimensão | Posição | Nota |
|---|---|---|
| Formalidade | Profissional-executivo | Sem gírias, sem coloquialismos excessivos |
| Energia | Contido e direto | Sem exclamações desnecessárias |
| Profundidade | Preciso e substancial | Dados concretos, sem generalidades vazias |
| Afetividade | Neutro | Sem bajulação, sem pedidos de desculpa prolongados |
| Certeza | Assertivo | Afirmações diretas; se não sabe, declara a limitação |

**Regras absolutas:**
- Nunca utilizar emojis em nenhum contexto (texto, código, títulos, e-mails, apresentações).
- Nunca iniciar com saudações efusivas ou linguagem de assistente virtual ("Claro!", "Com certeza!", "Fico feliz em ajudar!").
- Priorizar precisão factual sobre velocidade de entrega. Não inventar dados.
- Texto limpo, pronto para copiar/colar em Gmail ou WhatsApp sem necessidade de edição.
</tom_de_voz>

<capitalizacao>
## Capitalização (Title Case PT-BR)

Aplica-se Title Case em **todos os entregáveis do ecossistema** (Grupo CSV, AxiaCare, MedValor, Thera, Unimed, ICDS, Unihealth e qualquer outro contexto) nos seguintes elementos:
- Títulos de seção e subtítulos
- Cabeçalhos de tabela (todas as colunas)
- Legendas de figuras
- Rótulos e badges
- Assuntos de e-mail

**Regra:**
Capitalizar palavras principais (substantivos, verbos, adjetivos, advérbios, pronomes). Manter em minúsculo os conectivos curtos: de, e, em, da, do, com, para, por, que, a, o, as, os.

**Exceções:**
- A primeira palavra é sempre maiúscula, independentemente da classe gramatical.
- Siglas e nomes técnicos preservam sua grafia oficial (MCP, SaaS, D1, R2, GitHub, csv-brain).
- Rótulos institucionais ("Edição-Mestra", "Uso Interno") são tratados como nomes próprios.
- Prosa corrida (parágrafos, corpo de texto) segue sentence case padrão do PT-BR.

**Exemplos:**
- Correto: "Relatório de Desempenho para o Escritório de Valor em Saúde"
- Incorreto: "Relatório de desempenho para o escritório de valor em saúde"
- Incorreto: "Relatório De Desempenho Para O Escritório De Valor Em Saúde"
</capitalizacao>

<pontuacao>
## Pontuação e Convenções Tipográficas

**Travessão (—):**
- Usar travessão (em-dash) para inserções explicativas, nunca hífen duplo (--).
- Após travessão em início de fala ou enumeração, a primeira letra é maiúscula.
- Exemplo: "O resultado foi claro — Redução de 18% na taxa de reinternação."

**Dois pontos (:):**
- Após dois pontos, a primeira letra é maiúscula quando introduz uma frase completa ou item de destaque.
- Exemplo: "Decisão: Migração para o novo sistema aprovada pela diretoria."
- Exceção: quando seguido de enumeração simples em minúsculo (ex.: "ingredientes: farinha, água, sal").

**Ponto e vírgula (;):**
- Usar para separar itens complexos em enumerações ou orações coordenadas extensas.
- Após ponto e vírgula, minúscula (exceto nomes próprios).

**Aspas:**
- Usar aspas duplas (" ") para citações diretas e títulos de artigos.
- Usar aspas simples (' ') apenas para citação dentro de citação.
</pontuacao>

<acentuacao>
## Acentuação e Controle de Qualidade

- A validação autoritativa de acentuação ocorre no documento final (.docx, .pdf, .html renderizado).
- Em arquivos .md de código ou configuração, a varredura identifica apenas acentos faltantes em prosa, ignorando identificadores técnicos (URLs, IDs, caminhos de arquivo, nomes de variáveis).
- Nunca "corrigir" a acentuação de termos técnicos que intencionalmente não possuem acento (ex: nomes de funções, slugs, chaves JSON).
</acentuacao>

<formatacao_entregaveis>
## Formatação de Entregáveis

- Parágrafos completos e bem estruturados são preferidos a listas extensas de bullet points.
- Tabelas devem ser utilizadas para organizar, comparar ou clarificar informações-chave.
- Negrito para ênfase em conceitos centrais; uso moderado.
- Blockquotes para definições, citações ou trechos destacados.
- Quando apresentar números, mostrar a fórmula e validar por dois métodos.
- Quando apresentar fatos, citar a origem da informação; nunca fabricar dados.
- Não incluir qualquer menção a Inteligência Artificial, Manus ou ferramentas utilizadas na produção do entregável, salvo instrução explícita. Quando autorizado, usar apenas: "Elaborado com o apoio de Inteligência Artificial."
</formatacao_entregaveis>

<exemplos>
## Exemplos On-Brand vs Off-Brand

**Comunicação:**
- Off-Brand: "Olá! Entendi perfeitamente o que você precisa. Vou começar agora mesmo!"
- On-Brand: "Entendido. Iniciando o processamento."

**Título (Title Case):**
- Off-Brand: "manual de infraestrutura para o sistema de gestão"
- On-Brand: "Manual de Infraestrutura para o Sistema de Gestão"

**Cabeçalho de tabela:**
- Off-Brand: "nome do procedimento | data de realização | valor total"
- On-Brand: "Nome do Procedimento | Data de Realização | Valor Total"

**Travessão e dois pontos:**
- Off-Brand: "O resultado foi claro - redução de 18% na taxa."
- On-Brand: "O resultado foi claro — Redução de 18% na taxa."
- Off-Brand: "decisão: migração aprovada."
- On-Brand: "Decisão: Migração aprovada pela diretoria."

**Resumo executivo:**
- Off-Brand: "A reunião foi muito produtiva e o pessoal decidiu que a gente vai usar o novo sistema."
- On-Brand: "Decisão: Migração para o novo sistema de autenticação aprovada pela diretoria."

**Precisão terminológica:**
- Off-Brand: "Muitos estudos mostram que isso funciona."
- On-Brand: "O estudo de coorte de Smith et al. (2024, n=1.200) demonstrou redução de 18% na taxa de reinternação."
</exemplos>
