# AI Agent Prompts

💡 Curated prompts for AI Agent tools like GitHub Copilot, Cursor, Claude, and more.

This repository is structured to provide reusable, practical, and agent-specific prompts that can accelerate development workflows using modern AI tooling.

> The first prompt here bootstraps this very repository. Yes, it's AI inception. 🤖

## Usage

Each prompt in this repository is written in Markdown and can be used with different AI agent CLIs.

### 🚀 GitHub Copilot CLI

If you have [GitHub Copilot CLI](https://docs.github.com/en/copilot/github-copilot-cli/getting-started-with-github-copilot-cli) installed:

```bash
gh copilot suggest prompts/bootstrap-repo.md
```

It will read the file and generate commands or code based on the task described in the prompt.

### 🧠 OpenAI Codex CLI

If you have [Codex CLI](https://github.com/openai/openai-codex) installed:

```bash
codex
```

Then manually **copy and paste** the contents of `prompts/bootstrap-repo.md` into the terminal.

> ⚠️ Codex CLI currently does **not** support reading files via pipe (`cat file.md | codex`). You must paste the prompt manually due to input limitations related to raw mode.
