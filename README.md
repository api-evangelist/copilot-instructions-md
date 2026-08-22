# copilot-instructions.md (copilot-instructions-md)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
