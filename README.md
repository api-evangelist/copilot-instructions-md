# copilot-instructions.md (copilot-instructions-md)

copilot-instructions.md is a GitHub Copilot custom instructions file placed at .github/copilot-instructions.md in a repository. It provides repository-specific guidance and preferences that GitHub Copilot Chat, Copilot in the IDE, and the Copilot coding agent automatically inject into prompts when working in the repository. The file is plain Markdown in natural language, helping the AI understand build, test, validation, framework, and style conventions so it can produce code that is consistent with the project's expectations and reduce pull request rejections caused by avoidable lint, CI, or convention failures.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/copilot-instructions-md/refs/heads/main/apis.yml)

## Type

- **x-type:** standard

## Tags:

 - AI Coding, Coding Standards, Copilot, Custom Instructions, Developer Workflow, GitHub, GitHub Copilot, Markdown, Repository

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-04-28

## APIs

### copilot-instructions.md Format

The copilot-instructions.md format is an unstructured Markdown file placed at .github/copilot-instructions.md. GitHub Copilot detects the file automatically and prepends its contents to prompts sent to the model in Copilot Chat, Copilot in the IDE, and the Copilot coding agent. The file accepts free-form natural language instructions, with whitespace between sections ignored, and is rendered as a reference in Copilot Chat replies so users can confirm it was consulted.

**Human URL:** [https://docs.github.com/en/copilot/customizing-copilot/adding-repository-custom-instructions-for-github-copilot](https://docs.github.com/en/copilot/customizing-copilot/adding-repository-custom-instructions-for-github-copilot)

#### Tags:

 - Convention, GitHub Copilot, Markdown, Repository

#### Properties

- [Documentation](https://docs.github.com/en/copilot/customizing-copilot/adding-repository-custom-instructions-for-github-copilot)
- [Blog](https://github.blog/changelog/2025-01-23-custom-instructions-for-github-copilot-in-vs-code-now-generally-available/)
- [Documentation](https://docs.github.com/en/copilot/customizing-copilot/about-customizing-github-copilot-chat-responses)
- [Examples](https://github.com/github/awesome-copilot)

#### Features

- Auto-loaded by GitHub Copilot Chat, IDE plugins, and coding agent
- Resides at the canonical path .github/copilot-instructions.md
- Plain Markdown - no required schema or front matter
- Visible reference in Copilot Chat replies that consume the file
- Pairs with .github prompt files and Copilot agent rulesets
- Effective immediately upon save; no Copilot configuration step

#### Use Cases

- Telling Copilot which test runner, linter, and build commands to use
- Steering Copilot to preferred libraries or framework patterns
- Communicating commit message and branch naming conventions
- Documenting code style, naming, and comment conventions
- Reducing CI failures caused by Copilot generated code

### Copilot Instructions Ecosystem

Repository copilot-instructions.md is one layer in a stack of GitHub Copilot customization options. Personal custom instructions apply to a single user across all repositories. Organization custom instructions apply to every repository in a GitHub organization. Path-scoped .github/instructions/*.instructions.md files target specific files or globs. Prompt files in .github/prompts/ provide reusable named prompts. The copilot-instructions.md file sits at the repository tier and travels with the code, providing the same context to every collaborator.

**Human URL:** [https://docs.github.com/en/copilot/customizing-copilot](https://docs.github.com/en/copilot/customizing-copilot)

#### Tags:

 - AI Coding, Conventions, GitHub Copilot

#### Properties

- [Documentation](https://docs.github.com/en/copilot/customizing-copilot)
- [Documentation](https://docs.github.com/en/copilot/customizing-copilot/adding-personal-custom-instructions-for-github-copilot)
- [Documentation](https://docs.github.com/en/copilot/customizing-copilot/adding-organization-custom-instructions-for-github-copilot)
- [Documentation](https://docs.github.com/en/copilot/customizing-copilot/adding-prompt-files-to-your-repository)

#### Features

- Composes with personal and organization-level instructions
- Path-scoped .instructions.md files override repo-wide instructions
- Reusable prompts in .github/prompts/*.prompt.md
- Effective in Copilot Chat, Copilot in IDE, and Copilot coding agent
- Versioned and reviewed alongside code through pull requests

#### Use Cases

- Applying organization-wide guardrails across all repos
- Layering repo-specific rules on top of organization defaults
- Targeting language-specific conventions to subdirectories
- Sharing reusable named prompts with all collaborators

## Common Properties

- [Documentation](https://docs.github.com/en/copilot/customizing-copilot/adding-repository-custom-instructions-for-github-copilot)
- [Documentation](https://docs.github.com/en/copilot/customizing-copilot)
- [Examples](https://github.com/github/awesome-copilot)
- [Blog](https://github.blog/changelog/2025-01-23-custom-instructions-for-github-copilot-in-vs-code-now-generally-available/)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
