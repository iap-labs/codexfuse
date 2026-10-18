# CodexFuse

**See your Codex 5-hour and weekly limits, and when they reset, in a local Windows dashboard.**

[Try the free browser demo](https://iaplabs.itch.io/codexfuse-demo) · [Get CodexFuse for Windows (US$3.99)](https://iaplabs.itch.io/codexfuse)

[English](#english) · [Português (Brasil)](#português-brasil)

> This repository holds the README and links only. The app source code is not published here.

## English

CodexFuse is a local dashboard for monitoring your Codex usage limits: used and available percentage, a countdown to the next reset, detected consumption, hourly usage, and recent history.

### What it shows (version 1.4.0)

- Live limit first, history loads in the background.
- Countdown to the next reset and your account plan.
- 5-hour, weekly, and other windows shown separately.
- History with a 5-hour or weekly selector, titled by the real window, and CSV export that identifies each series.
- Alerts at 20%, 10%, and 5% remaining, without repeating on every refresh.
- The last confirmed limit stays on screen if a read fails, and history is never shown as the current limit.

### How to use

1. Download and extract the Windows ZIP from the [itch.io page](https://iaplabs.itch.io/codexfuse).
2. Open `CodexFuse.exe`.
3. The app finds your local Codex sessions automatically. If needed, pick the `sessions` folder by hand.
4. Use the **EN / PT** button at the top to switch the interface language.

No installation, sign-in, API key, or extra account. Requires Windows 10/11 and prior local Codex use that creates limit samples.

### Data and privacy

CodexFuse reads only `payload.rate_limits` from the local Codex session JSONL files. It does not retain, export, or send prompts, responses, attachments, or credentials, and it never opens `auth.json`. Your data stays on your PC.

Figures are percentage samples reported by Codex, not exact token or billing measurements. The official Codex Usage panel remains the source of truth.

### Feedback

Questions and bug reports are welcome in this repository's Issues.

## Português (Brasil)

CodexFuse é um painel local para Windows 10/11 que mostra o limite do Codex (usado e disponível), a contagem até a próxima redefinição, as janelas de 5 horas e semanal, o uso por hora e o histórico recente.

Extraia o ZIP e abra `CodexFuse.exe`. Sem instalação, login extra ou chave de API. O app lê só os rate limits das sessões locais do Codex e não envia prompts, respostas nem credenciais.

[Demo grátis no navegador](https://iaplabs.itch.io/codexfuse-demo) · [Versão para Windows (US$3.99)](https://iaplabs.itch.io/codexfuse)

---

CodexFuse is an independent product by IAP Labs and is not affiliated with, endorsed by, or sponsored by OpenAI. "Codex" is used only to describe compatibility.
