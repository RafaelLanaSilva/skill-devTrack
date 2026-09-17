---
name: devtrack-capture
description: Capture a privacy-safe professional development experience from the current Codex session, prepare it for review, and save it to DevTrack/Inbox only after explicit user confirmation.
metadata:
  short-description: "Registrar experiências técnicas"
---

# DevTrack Capture

Use when the user invokes $devtrack-capture after a development activity. Analyze only evidence available in the current session: conversation, request, problem, changed files, Git diff, commands, tests, decisions, limitations, and difficulties. Never invent facts; use Não informado when unclear.

## Required workflow

1. Interpret the activity and identify title, current date (AAAA-MM-DD), category, project, technologies, context, problem, investigation, cause when evidenced, alternatives, solution, validation, result, learnings, and competencies.
2. Produce a complete independent Markdown record with frontmatter: tipo: experiencia, data, categoria, projeto, tecnologias, status: aguardando-revisao. Include sections Contexto, Problema ou necessidade, Investigação e diagnóstico, Causa identificada, Abordagens consideradas, Solução aplicada, Validação e testes, Resultado, O que aprendi, Competências demonstradas, Como explicar em uma entrevista (Resposta curta, Resposta técnica completa, Estrutura STAR), and Possíveis perguntas técnicas.
3. Keep answers faithful to evidence and include Situação, Tarefa, Ação, Resultado in STAR. Do not leave placeholders.
4. Show the full Markdown and ask the user to review it and confirm it is correct and free of confidential information. Do not save before explicit confirmation. Revise and show it again if requested.
5. After unambiguous confirmation, save to the existing Google Drive folder DevTrack/Inbox/ when connected. Never create a duplicate DevTrack folder or touch Experiencias, Entrevistas, Resumos Semanais, or Competências. If Drive is unavailable, use a local inbox path only if configured by the user/environment; otherwise explain that saving could not be completed. State the actual location.

## Privacy

Never record source code or excerpts, credentials, tokens, API keys, private URLs, client/person names, internal system/database/table names, private endpoints, servers, personal, commercial, or strategic data. Generalize as sistema interno, cliente, aplicação corporativa, serviço da aplicação, tabela de dados, or ambiente de desenvolvimento. If uncertain, use Não informado and flag for review.

## Filename and boundaries

Use AAAA-MM-DD-titulo-curto.md, lowercase, no accents, hyphen-separated. Never overwrite an existing file; append a short identifier or numeric suffix on collision. This skill only captures experiences: never commit, alter project files, send code, publish, create issues, send messages, or run unrelated external changes. It must not capture automatically without invocation.
