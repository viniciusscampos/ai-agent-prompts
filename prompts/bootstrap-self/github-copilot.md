# Task: Bootstrap this repository with initial structure and documentation

## Goal

Generate the foundational structure for a prompt repository that provides curated AI prompts adapted to different AI Agents such as GitHub Copilot, Cursor, Claude, etc.

## Instructions

- Create the following folder structure:
  - `prompts/` — root for all prompts
  - Each subfolder represents a prompt category (e.g. `pr-description/`, `test-generator/`, etc)
  - Inside each subfolder, create one `.md` file per agent (`github-copilot.md`, `claude.md`, etc.)

- Generate the initial README.md for the repository with:
  - A project title and description
  - A section explaining how to use the prompts via CLI
  - A section on how to contribute
  - A badge or example usage snippet (e.g., with `gh copilot suggest`)

- Do not generate any prompts yet, only placeholder folders and instructions.

## Output format

- Return a list of files to be created and their suggested content in Markdown.
- Format responses for easy copy-paste into an initialized repo.
