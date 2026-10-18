# Tutor Pessoal de Carreira Tech

**DcsProducer®** · artefato do **#7DaysOfCode — Prompt Engineering**

Mega-prompt e estrutura mínima de um **tutor pessoal de carreira tech**: diagnóstico de perfil, gaps, plano de 7 dias e revisão semanal — alinhado à skill `career-gap-analyzer` e à rota `/carreira` do [Tesseract](https://github.com/producerdcs-cpu/tesseract).

> Não substitui o gate ativo do Hub (**NeuroLeitor**). É evidência de carreira / prompt engineering.

---

## Conteúdo

| Path | Função |
|------|--------|
| [`prompts/MEGA_PROMPT.md`](prompts/MEGA_PROMPT.md) | Sistema + usuário: tutor de carreira |
| [`prompts/SEMANA_7_DIAS.md`](prompts/SEMANA_7_DIAS.md) | Roteiro #7DaysOfCode |
| [`examples/sessao-exemplo.md`](examples/sessao-exemplo.md) | Exemplo de sessão estruturada |
| [`docs/ENCAIXE_ECOSSISTEMA.md`](docs/ENCAIXE_ECOSSISTEMA.md) | Ligação Hub · Tesseract · career-gap |

---

## Como usar

1. Abra `prompts/MEGA_PROMPT.md`.
2. Cole o bloco **System** no seu LLM (Grok, ChatGPT, Claude, etc.).
3. Cole o bloco **User template**, preenchendo o perfil.
4. Siga o plano de 7 dias em `prompts/SEMANA_7_DIAS.md`.

Opcional: cruzar o output com a matriz de competências em **Tesseract → `/carreira`** ou com a skill **career-gap-analyzer** no Grok.

---

## Stack deste repo

- Markdown only (MVP de conteúdo)
- Sem deploy obrigatório
- Sem API keys

Evolução natural: app leve (React) ou integração no Hub — **fora** deste seed.

---

## Status (18/10/2026)

| Item | Estado |
|------|--------|
| Repo seed | ✅ |
| Mega-prompt | ✅ |
| Plano 7 dias | ✅ |
| App / deploy | — não previsto neste seed |

© DcsProducer® Creative Studio
