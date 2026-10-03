# 🤖 Agentes de IA (Prioridade Alta)

[← Voltar ao índice](../README.md)

## 1. Hermes Agent + NemoClaw (NVIDIA) — Recomendado para a empresa

Agente auto-melhorável que aprende com o fluxo de trabalho do time e cria **Skills** reutilizáveis.

- [Blueprint NemoClaw for Hermes](https://build.nvidia.com/nvidia/nemoclaw-for-hermes-agent)
- [Documentação oficial NemoClaw](https://docs.nvidia.com/nemoclaw/)
- [Quickstart com Hermes](https://docs.nvidia.com/nemoclaw/get-started/quickstart-hermes)
- [GitHub NemoClaw](https://github.com/NVIDIA/NemoClaw)
- [Hermes Agent (Nous Research)](https://github.com/NousResearch/hermes-agent)

**Instalação rápida:**

```bash
curl -fsSL https://www.nvidia.com/nemoclaw.sh | NEMOCLAW_AGENT=hermes bash
```

> ⚠️ Antes de rodar qualquer `curl | bash`, baixe e leia o script.

## 2. Outros agentes de código (escolha conforme o fluxo)

| Agente | Tipo | Melhor para | Link |
|---|---|---|---|
| Cursor | IDE completa | Uso diário (mais polido) | [cursor.com](https://cursor.com) |
| Claude Code | Agente de terminal | Tarefas longas e complexas | [Docs do Claude Code](https://docs.claude.com/en/docs/claude-code/overview) |
| Aider | Terminal + Git | Fluxo git-nativo e transparente | [aider.chat](https://aider.chat) |
| Cline | Extensão VS Code | Open-source + controle total | [cline.bot](https://cline.bot) |
| Windsurf | IDE agêntica | Planejamento multi-step | [windsurf.com](https://windsurf.com) |
| GitHub Copilot | Extensão / IDE | Integração profunda com GitHub | [github.com/features/copilot](https://github.com/features/copilot) |
| OpenAI Codex | Agente de terminal / nuvem | Tarefas delegadas em paralelo | [developers.openai.com/codex](https://developers.openai.com/codex) |
| Gemini CLI | Agente de terminal | Open-source, contexto grande | [github.com/google-gemini/gemini-cli](https://github.com/google-gemini/gemini-cli) |
| Continue | Extensão VS Code / JetBrains | Open-source, modelos configuráveis | [continue.dev](https://www.continue.dev) |
| Zed | Editor com IA | Editor rápido, colaboração | [zed.dev](https://zed.dev) |

## Recomendação interna

- Uso diário → **Cursor**
- Tarefas complexas / refactors grandes → **Claude Code** ou **Hermes**
- Transparência total + commits automáticos → **Aider**

> Regras de uso em produção: [regras/uso-de-ia-em-producao.md](../regras/uso-de-ia-em-producao.md)
