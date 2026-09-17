# devtrack-capture

Skill global do Codex para registrar experiências técnicas de desenvolvimento em Markdown, com foco em aprendizado, decisões técnicas e preparação para entrevistas.

## O que faz

- Analisa o contexto disponível da sessão do Codex.
- Gera um registro completo e independente em Markdown.
- Remove ou generaliza informações confidenciais.
- Inclui respostas curta, técnica completa e estrutura STAR para entrevistas.
- Solicita revisão e confirmação antes de salvar.

## Instalação global

Copie esta pasta para o diretório global de skills do Codex:

```text
Windows: C:\Users\<seu-usuário>\.codex\skills\devtrack-capture
macOS/Linux: ~/.codex/skills/devtrack-capture
```

Depois, reinicie ou recarregue o Codex.

## Uso

```text
$devtrack-capture
```

Também é possível fornecer uma instrução:

```text
$devtrack-capture registre a atividade concluída nesta sessão
```

A skill não salva o registro sem confirmação explícita do usuário. A pasta padrão de destino é `DevTrack/Inbox/` no Google Drive conectado, quando essa integração estiver disponível.

## Estrutura

```text
devtrack-capture/
├── SKILL.md
├── README.md
└── agents/
    └── openai.yaml
```

## Privacidade

Não inclua código-fonte, credenciais, tokens, chaves de API, URLs privadas, nomes de clientes ou pessoas, sistemas internos, dados pessoais, comerciais ou estratégicos. Revise o Markdown antes de confirmar o salvamento.
